This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## WhatsApp Web QR Scanner

This project includes a beautiful WhatsApp Web QR scanning interface built with shadcn/ui components. The interface provides:

### Features
- **Real-time Status Updates**: Automatically polls the server for status changes
- **QR Code Display**: Shows the QR code when ready for scanning
- **Status Indicators**: Visual feedback for different connection states
- **Responsive Design**: Works on desktop and mobile devices
- **Error Handling**: Comprehensive error states with troubleshooting tips

### Setup
1. Navigate to `/setup` to access the QR scanner
2. The interface will automatically fetch the initial status
3. When QR code is ready, scan it with your WhatsApp mobile app
4. The interface will automatically detect when connection is successful

### Environment Variables
Create a `.env.local` file with:
```
NEXT_PUBLIC_API_URL=your-api-server-url
```

### Components Used
- **shadcn/ui**: Card, Button, Badge, Separator, Skeleton
- **Lucide React**: Icons for status indicators
- **Tailwind CSS**: Styling and animations

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.

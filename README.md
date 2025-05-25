# Biofuel Project

A Next.js application with Supabase integration for biofuel data management and analysis.

## Tech Stack

- Next.js 14
- TypeScript
- Supabase
- Tailwind CSS

## Getting Started

1. Clone the repository
```bash
git clone https://github.com/derouett/Biofuel.git
```

2. Install dependencies
```bash
npm install
```

3. Create a `.env.local` file with your Supabase credentials:
```env
NEXT_PUBLIC_SUPABASE_URL=your-project-url
NEXT_PUBLIC_SUPABASE_ANON_KEY=your-anon-key
SUPABASE_SERVICE_ROLE_KEY=your-service-role-key
```

4. Run the development server
```bash
npm run dev
```

## Deployment

This project is configured for deployment on Vercel. To deploy:

1. Push your code to GitHub
2. Import your repository on Vercel
3. Add your environment variables in the Vercel dashboard
4. Deploy!

## Environment Variables

Make sure to set these environment variables in your Vercel project settings:

- `NEXT_PUBLIC_SUPABASE_URL`
- `NEXT_PUBLIC_SUPABASE_ANON_KEY`
- `SUPABASE_SERVICE_ROLE_KEY`

## Development

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm start` - Start production server
- `npm run lint` - Run ESLint
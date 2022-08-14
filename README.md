# Simple React Blog
<img width="1274" alt="simple-react-blog" src="https://user-images.githubusercontent.com/1950722/173696384-bbfac078-0221-4693-a819-6f08b5a4d14b.png">


### React + Next.js + Cosmic
This blog uses Next.js to create a React blog.  It connects to the Cosmic API via the [Cosmic NPM module](https://www.npmjs.com/package/cosmicjs).  Manage your content from your Cosmic Bucket Dashboard.  Simple

## Getting Started
1. Log in to Cosmic and install the [Simple React Blog template](https://www.cosmicjs.com/apps/simple-react-blog).
2. Run the following commands to install the code locally.
```
git clone https://github.com/pushp1607/Expresate-Blog
cd simple-react-blog
```
#### Environment Variables

1. Create an `.env.local` file to gain API access to your Cosmic Bucket. To do this, run:
```
cp .env.example .env.local
```
2. Find your API access keys at <em>Bucket Settings &gt; API Access</em> and add them to the `.env.local` file. It should look something like this:
```
NEXT_PUBLIC_COSMIC_BUCKET_SLUG=your-bucket-slug
NEXT_PUBLIC_COSMIC_READ_KEY=your-bucket-read-key
```

#### Run in development
Install all dependencies and run in development mode.
```
yarn
yarn dev
```
Open [http://localhost:3000](http://localhost:3000).

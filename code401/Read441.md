# What we will learn

- React 4

The source of this summary [The First link](https://nextjs.org/learn/basics/dynamic-routes)

The source of this summary [The Second link](https://nextjs.org/learn/basics/deploying-nextjs-app)

_______________________________________

## Dynamic Routes

**It is the case where each page path depends on external data. Next.js allows you to statically generate pages with paths that depend on external data. This enables dynamic URLs in Next.js.**

### How to Statically Generate Pages with Dynamic Routes:

- We want each post to have the path /posts/<id>, where <id> is the name of the markdown file under the top-level posts directory.
  
- Since we have ssg-ssr.md and pre-rendering.md, we’d like the paths to be /posts/ssg-ssr and /posts/pre-rendering.

### Implement getStaticPaths
  
**we should set up the files:**

1. Create a file called [id].js inside the pages/posts directory.
2. Remove first-post.js inside the pages/posts directory — we’ll no longer use this.
3. Open pages/posts/[id].js in your editor and paste the following code.
  
            import Layout from '../../components/layout'

          export default function Post() {
            return <Layout>...</Layout>
          }
  
 ## Deploying Your Next.js App
  
 ### Push to GitHub 
  
**Before  deploy,  push our Next.js app to GitHub. This will make deployment easier.**

- On  personal GitHub account, create a new repository called nextjs-blog.
- The repository can be public or private. You do not need to initialize it with a README or other files.
- If you haven’t initialized the git repository locally for your Next.js app, do so now.
-  Push the Next.js app to  GitHub repository.
  
### To push to GitHub, you can run the following commands (replace <username> with your GitHub username)
- 'git remote add origin https://github.com/<username>/nextjs-blog.git'
- 'git push -u origin main '
  
### Deploy to Vercel
  
**The easiest way to deploy Next.js to production is to use the Vercel platform developed by the creators of Next.js.**

*Vercel is a serverless platform for static and hybrid applications built to integrate with your headless content, commerce, or database.make it easy for frontend teams to develop, preview, and ship delightful user experiences, where performance is the default.*

### Create a Vercel Account
  
- First, go to https://vercel.com/signup to create a Vercel account.Choose Continue with GitHub and go through the sign up process.

- Import your nextjs-blog repository
  
- Once you’re signed up, import your nextjs-blog repository on Vercel. You can do so from here: https://vercel.com/import/git.
  - need to Install Vercel for GitHub. You can give it access to All Repositories.
  - Once installed Vercel, import nextjs-blog.
  
**Vercel automatically detects that you have a Next.js app and chooses optimal build settings for you.**

1. Project Name
2. Root Directory
3. Build Command
4. Output Directory
5. Development Command

**Vercel is made by the creators of Next.js and has first-class support for Next.js.When you deploy your Next.js app to Vercel, the following happens by default:**

- Pages that use Static Generation and assets (JS, CSS, images, fonts, etc) will automatically be served from the Vercel Edge Network, which is blazingly fast.
  
- Pages that use Server-Side Rendering and API routes will automatically become isolated Serverless Functions. This allows page rendering and API requests to scale infinitely.

#### Vercel has many more features, such as:

1. Custom Domains: 
  
*Once deployed on Vercel, assign a custom domain to your Next.js app.* 
  
2. Environment Variables: 

*can also set environment variables on Vercel. You can then use those environment variables in Next.js app.*

3. Automatic HTTPS:
  
*HTTPS is enabled by default (including custom domains) and doesn't require extra configuration.*
  

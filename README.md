# Deploy with NetlifyPress

![Deploy with NetlifyPress](http://ps.w.org/deploy-netlifypress/assets/banner-1544x500.png)

### Description
Instead of going into [Netlify](https://netlify.com) and triggering a deploy everytime you make a change in WordPress, automate and make things easier with the **Deploy with NetlifyPress** plugin. **Deploy with NetlifyPress** lets you trigger deploys in [Netlify](https://netlify.com) (automatically!) without having to leave your WordPress Dashboard.

### Use Cases
So, you've build a headless static front-end for your WordPress site and hosted it on [Netlify](https://netlify.com), good job! Wondering how would you trigger a deploy in [Netlify](https://netlify.com) everytime someone updates a post in WordPress? Forget going inside everytime an update is made and triggering a build manually, install **Deploy with NetlifyPress** and let it run a deploy for you automatically on each update.

If you're looking for a real-life example, I've build my personal site [nahid.dev](https://nahid.dev) ([GitHub](https://github.com/nfmohit-wpmudev/nahid.dev)) using [GatsbyJS](https://www.gatsbyjs.org/) with its source as WordPress and am hosting it on [Netlify](https://netlify.com). I use **Deploy with NetlifyPress** to automate deploys when I update pages and posts.

### Core Features
The core features of the plugin include the abilities to:
* Automatically trigger deploys on post publish
* Automatically trigger deploys on post update
* Automatically trigger deploys on post trash
* Filter the post types for which you want automatic deploys to run
* Add a button for manual deployments on the top admin toolbar.

### Requirements
This plugin requires you have a site hosted on Netlify and a Build Webhook URL set up. Here's how you can get a Build Hook URL:
1. Log into [Netlify](https://app.netlify.com/).
2. From the list of sites, enter the site you want to set up **Deploy with NetlifyPress** for.
3. Go to *Site settings*.
4. From the left sidebar, go to *Build and deploy→Continuous Deployment*.
5. Scroll down to the "*Build hooks*" section.
6. Click the *Add build hook* button, enter a preferred name for the webhook (e.g. "Deploy from WordPress"), choose the [Git](https://git-scm.com/) branch to build and hit *Save*.
7. You'll be given a Build Hook URL that can be used in **Deploy with NetlifyPress**.

### Install
#### Automatic Installation
1. Go to your *WordPress Dashboard→Plugins→Add New*.
2. Search for **"Deploy with NetlifyPress"**.
3. Click on **"Install"**.
4. Once installed, click on **"Activate"**.

#### Manual Installation
1. Download the plugin *.zip* folder using the download button on this page.
2. Go to your *WordPress Dashboard→Plugins→Add New*.
3. Click on the **"Upload Plugin"** button.
4. Upload the downloaded *.zip* file.
5. Activate it.

### Usage
1. Install and activate the plugin
2. Go to your *WordPress Dashboard→NetlifyPress*
3. On the "*Connect with Netlify*" tab, enter your Netlify Build Hook URL.
4. On the "*Automatic Deployment*" tab, choose if you want to use Automatic Deployment, on which actions should it trigger and which post types the actions should apply to.
5. On the "*Manual Deployment*" tab, choose if you want to add a "Trigger Netlify Deploy" manual trigger button in the top admin toolbar.

### Support
If the above usage steps don't answer your question(s), if you want to report an issue or if something is not working as expected, please create a topic in the [Support Forum](https://wordpress.org/support/plugin/deploy-netlifypress/).

### Roadmap
I have plans for the following features/improvements in the coming days (subject to user feedback and usage):
1. Admin options migration to Settings API with Ajax support.
2. Success/failure message on auto deploy trigger.
3. Success/failure message on auto deploy status (after completion).
4. Scheduled deployments.
5. Deployment logs.

### Contribute
If you want to contribute to the plugin by reporting issues, implementing new features and so on, [here's its development repository on Github](https://github.com/nfmohit-wpmudev/deploy-netlifypress).

### Sponsor
You can sponsor this project and support my open-source development by [becoming a Patron](https://www.patreon.com/nfmohit)!

### Frequently Asked Questions

**Is this plugin free?**
Definitely! Deploy with NetlifyPress is free and always will be.

**How many deploys can I trigger?**
Unlimited.

# tempx

Deploy Astro + Starlight, deploy Gitlab. Run.

```
sudo dnf module list nodejs
sudo dnf module enable nodejs:22
sudo dnf install nodejs -y
sudo yum install npm
node -v
npm -v
```

- Choose Blog style. Yes on Git

```
npm create astro@latest -- --template starlight
```

```
sudo firewall-cmd --permanent --add-port=4321/tcp
sudo firewall-cmd --reload
```

Run
```
npm run dev -- --host
```
Notes

- http://130.61.100.26:4321

```
Here are a few ideas on how to get started with the template:

Edit this page in src/pages/index.astro
Edit the site header items in src/components/Header.astro
Add your name to the footer in src/components/Footer.astro
Check out the included blog posts in src/content/blog/
Customize the blog post page layout in src/layouts/BlogPost.astro
```

http://130.61.100.26:4321/

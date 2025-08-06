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
npm create astro@latest
npx astro add starlight
```

```
sudo firewall-cmd --permanent --add-port=4321/tcp
sudo firewall-cmd --reload
```

Run
```
npm run dev -- --host
```

This website is built on a local Ghost instance which I compile to a static site.

This `README.md` is for me to remember how to edit and deploy this as my memory continues to fail me.

### Edit
1. Navigate to where your Ghost folder is locally.
2. Run `ghost start`.
3. Navigate to the link specified and edit your site.

### Deploy
1. Navigate to where your Ghost site has a git instance.
2. Run `rm -rf ./*`. (Scary, I know!)
3. Generate a static site with `gssg --url gusvieweg.github.io`.
4. Run `cp -r static/* . && rm -rf static/`.
5. Add your new post and push it to Github.

Good reference: https://dev.to/bassel/hosting-your-ghost-blog-on-github-pages-for-free-53hl

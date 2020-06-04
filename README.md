# taiwangoldcard.com

Our goal is to:
1. Increase the number of Gold Card Holders
2. Increase the profile of the Gold Card, cementing its position as a 'special' accomplishment
3. Rally the pool of Gold Card Holders to improve the life of all foreign residents in Taiwan
4. Raise the profile of Taiwan as a great place to live and work

## Website architecture

- Use https://gohugo.io with the [compose theme](https://github.com/onweru/compose)
- Hosted on github
- We use Cloudflare

## Working with the repo

### Setup the project
```bash
brew install hugo # check https://gohugo.io/getting-started/installing/ for alternative method 
git clone https://github.com/taiwangoldcard/goldcard.tw.git
cd goldcard.tw
hugo server #this launch a server and serve it at http://localhost:1313/
```

### Editing the content
`content` is where you should usually edit the content

### Editing the layout 
- `themes/compose/layout` is where you want to. modify the layout 
- `themes/compose/assets/js` is where you want to. modify the layout 
- `themes/compose/assets/sass` is where is the styles. `hugo` will automatically translates it to css 
- `docs` is the "build" folder, where github look at to show the taiwangoldcard.com website

### Deploy changes
`sh ./deploy.sh` 

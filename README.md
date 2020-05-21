`Next.js` expect a public folder at the root level, NEXT TO the `.next` (I really tried to avoid that pun)

Some images are indeed bundled, like `public/vercel.svg`, but others are not. We serve `public/my-image.png` from `index.js`.

1. Do a `yarn build`
2. Try `yarn start` --> you should see a cute cat images
3. `rm -rf public`
4. `yarn start` again --> the cat image will now be missing

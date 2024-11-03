viable

a simpler stack for building serverful web apps

- frontend (vite spa mode + pages)
- api (vinxi)
- database (sqlite + dbmate)
- durable workflows (inngest)
- auth (auth.js)
- tests (vitest)
- reactive db subscriptions for fe (soul)

for development:
```
npm run dev
```

to deploy to production:
```
git push
```

to install into a production server target
```
ssh yourserver
git clone thisrepo .
npm install
npm run production-install
```
Fullstack todo app to deepdive in `Next.js` and acquaint myself more closely with `Nest.js`

In plans: `users`, `todos` and `auth` endpoints, authentication (jwt access + refresh tokens), authorization?, also want to try redis, maybe divide into microservices in the future

Some general tasks 
- [ ] Create develop branch and use this branch for all future branches
- [ ] Set up development env both in client and server (eslint, prettier, ide settings, husky, commitizen, .emv)
- [ ] Think about folder structure
- [ ] Github? ci/cd
- [ ] Deploy to custom domain
      
Server: 
  - [ ] Set up prisma and connect to a database
  - [ ] Create models and relations between them
  - [ ] Auth endpoint
    - [ ] Login (simple)
    - [ ] Register (simple)
    - [ ] Add access token for login/register
    - [ ] Add refresh token for login/register
    - [ ] Email confirmation?
    - [ ] Password restoring?
  - [ ] Security (to not forget)
  - [ ] Users endpoint (not too much to do)
  - [ ] Todos endpoint (not too much to do)
  - [ ] Api documentation
  - [ ] Tests
     
Client:

Just simple ui to not spend too much time

Use `app` router

Split and organize good your code, think about scalability

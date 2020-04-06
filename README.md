
# Fullstack flask + typescrip + sass
Hello, this is a template project that I'm intentending to create my side projects, the ideia is to enable all dev in one place, easy, simple and fast. Fell free to copy.

it also have some sugars, like:
Gsap, Momentjs, Cleavejs and swup 

## usage:
  
#### Front-end:

`yarn install`

if you use npm, make sure to change the scripts on package.json

```json
//this:
{
    "dev": "yarn lint && yarn css:dev && yarn ts:dev",
    "prod": "yarn lint && yarn css:prod && yarn ts:prod"
}
    
//become:
{
    "dev": "npm run lint && npm run css:dev && npm run ts:dev",
    "prod": "npm run lint && npm run css:prod && npm run ts:prod"
}
```
for develoment run on a terminal window run:

```
yarn watch
// or
npm run watch
```

this will recompile sass and typescript on every change, alternativaly you can run:

```
yarn dev
// or
yarn prod
```

#### Back-end:

```shell
python3 -m venv venv
#window
. venv/scripts/activate //window
#linux, osx
. venv/.bin/activate
pip install -r requirements.txt
flask run
```
## TO-DO
and still missing some features:

- [ ] Example application code (front-end and back-end have no code yet)

#### front-end:

- [ ] Add workbox build script

- [ ] Add push notifications

- [ ] Create minimal css reset

- [ ] Create minimal css flexbox grid

- [ ] Create minimal css typo system

#### back-end:

- [ ] Save requirements.txt
- [ ] Add blueprints capabilities

###### Obs.: More backend capabilities will not be add since is project specific

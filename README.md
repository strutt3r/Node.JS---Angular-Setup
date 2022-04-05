# node-om1xzu

[Edit on StackBlitz ⚡️](https://stackblitz.com/edit/node-om1xzu)

##

I was having trouble running Angular from the Webcontainer as the NPM Start command initialized by StackBlitz's Turbo only checks for the Angular package at the root level.

##

The steps I used are as follows:

1. turbo install @angular/cli
2. rm package.json
3. ng new my-app --directory=./

##

This allows the project to initial and boot on loading.

# css-workshop
### Pilot Academy CSS/styling workshop

In order to generate usual `.css` files from included `.scss`, you should:
- make sure you have sass gem installed (`gem install sass`)
- use the gem with `sass main.scss main.css` to generate a main `.css` file OR
- fire up the watcher with `sass scss/main.scss:css/main.css --watch` - this will initally generate the main `.css` file in `/css` folder and watch for any changes made in `main.scss` file and update `main.css` accordingly

# css-workshop
### Pilot Academy CSS/styling workshop

In order to generate usual `.css` files from included `.scss`, you should:
- make sure you have sass gem installed (`gem install sass`)
- use the gem with `sass input_file.scss output_file.css` to generate a single file OR
- fire up the watcher with `sass --watch scss:css` - this will initally generate needed `.css` files in `/css` folder and watch for changes made in `/scss` directory and update files in `/css` folder accordingly.

# Wordpress development

## Local Setup

1. Run `docker compose up -d`
   - This will create a `wp-content/` folder.
2. Go to `./wp-content/themes/` and run `sudo chmod 777 ./`
   - Now you have permisson to make add/remove from this folder
3. Clone the theme file
4. You probably won't have permission to edit the folder so use this command (at your own risk)

```
sudo chmod -R 777 ./wp-content

```

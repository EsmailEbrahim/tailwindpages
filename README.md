## Tailwind Pages
Tailwind Pages App in Frappe

## Bench Commands
```
bench new-site tailwind.localhost
bench new-app tailwindpages
bench --site tailwind.localhost install-app tailwindpages
cd tailwindpages/
bench set-nginx-port tailwind.localhost 10000
sudo service nginx reload
```

## Node & Yarn Commands
```
npm init --yes
yarn add -D tailwindcss
npx tailwindcss init
npx tailwindcss -i ./tailwindpages/templates/base.css -o ./tailwindpages/public/css/styles.css
yarn run build
```
eslint initial command: "npm init @eslint/config"
find lint : npx eslint "**/\*{.ts,.tsx}" || eslint --ext .js,.jsx,.ts,.tsx src/
fix lint : npx eslint "**/\*{.ts,.tsx}" --fix || eslint --ext .js,.jsx,.ts,.tsx src/ --fix
add typescrip config on eslint config
install prettier : npm install --save-dev --save-exact prettier
install eslint-plugin-prettier : npm install --save-dev eslint-plugin-prettier
set extends prettier on eslint config
configure prettierignore and rc file
add prettier command on package.json

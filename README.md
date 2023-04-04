# gymlog-frontend

<!-- Note Important -->

1. Always build code with backward compatablity
2. Dont edit Dist files directly always use build
3. Core js is your friend.
4. Write css and js code in ./source-assets folder only

WEBPACK
run npm install
# ✅ Install Webpack globally
npm install -g webpack webpack-cli

# ✅ Create a symbolic link from the global package
# to node_modules/ of current folder
npm link webpack
run npx webpack --config webpack.config.js --watch

--watch option will keep looking for option and will build the file automatically

Reference https://webpack.js.org/guides/getting-started/
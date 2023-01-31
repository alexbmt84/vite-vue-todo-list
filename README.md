<h1>Vue 3 + Vite todo list :clipboard:</h1>

<h2>Setting Up a New Node Project from GitHub</h2>

<h3>Cloning is a process of downloading a repository from a remote server via using the clone command :computer: :</h3>

``bash
git clone https://github.com/UserName/RepoName.git
``

<p>The above clone command will download the project from a remote server locally. The node_modules is not a part of the cloned repository and should be downloaded using the npm install command to download all the defined and transitive dependencies mentioned in package.json file :computer: :</p>

<p>Make sure that you are in the root directory of the project, use pwd or cd for windows.</p>

``bash
cd RepoName
npm install
``

<p>It will take some time to download all the dependencies into the node_modules directory, and after the completion of this process, the project is ready to run :computer: :</p>

``bash
npm start
``

<h2>How to create a new Vue 3 + Vite template :memo: </h2>

<h3>Create... :computer:</h3>

```bash
npm create vite@latest . -- --template vue
```

<h3>Install... :computer: </h3>

```bash
npm install
```

This template should help get you started developing with Vue 3 in Vite. The template uses Vue 3 `<script setup>` SFCs, check out the [script setup docs](https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup) to learn more.

## Recommended IDE Setup

- [VS Code](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (and disable Vetur) + [TypeScript Vue Plugin (Volar)](https://marketplace.visualstudio.com/items?itemName=Vue.vscode-typescript-vue-plugin).

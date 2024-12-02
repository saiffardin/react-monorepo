### Doc Link: https://nx.dev/getting-started/tutorials/react-monorepo-tutorial

---

### Folder Structure

- One way to structure an Nx monorepo is to place application projects in the **apps** folder, and library projects in the **libs** folder.

- _Applications_ are encouraged to be as light-weight as possible so that more code is pushed into _libraries_ and can be reused in other projects.

- This folder structure is just a suggestion and can be modified to suit your organization's needs.

---

### JSON file info

- The [nx.json](https://nx.dev/reference/nx-json) file contains configuration settings for Nx itself and global default settings that individual projects inherit.

- The `apps/react-store/project.json` file contains [settings that are specific to the react-store project](https://nx.dev/reference/project-configuration). We'll examine that file more in the next section.

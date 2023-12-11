![Logo](https://www.browserstack.com/images/static/header-logo.jpg)

# Percy-figma Integration Example

---

## Repository setup

-   Clone the repository

-   Install Percy CLI

    ```sh
     npm install -g @percy/cli
    ```

-   Install dependencies:

    ```sh
     npm install
    ```

### Provide the correct parameters in the config file

```sh
percy_token: Percy Project Token
figma_token: Figma Account Access Token
figma_file_token: Figma File Token
ids: ["111-111", "222-222"]
names: ["Snapshot 1", "Snapshot 2"]
```

## Taking Snapshots

Execute :

```sh
npx percy-figma --config temp.yml
```
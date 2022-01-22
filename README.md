# Getting Started With Create Next App

1. Make a git repository (or clone an empty repository from a remote).

    ```sh
    mkdir -p ~/git/next-app
    cd ~/git/next-app
    git init
    ```

1. Install Yarn.

    ```sh
    npm install --global yarn
    ```

1. Create a Next app.

    ```sh
    yarn create next-app .
    ```

1. Disable telemetry.

    ```sh
    npx next telemetry disable
    ```

    This sets a flag in the Next configuration: `~/.config/nextjs-nodejs/config.json`.

    ```json
    {
        "telemetry": {
            "notifiedAt": "1642873541794",
            "anonymousId": "31d81dc158937266a7336e73c03e61348aa20702e42c9478fdefd1392ba10075",
            "salt": "b426ec4a6a76e3deebc65c921a8aaa63",
            "enabled": false
        }
    }
    ```

1. Commit and push.

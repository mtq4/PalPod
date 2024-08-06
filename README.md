# PalPod

**PalPod is the best Skyport Panel Dashboard, which allows you to:**

- **Resource Management**: Create and manage servers, gift resources, etc.
- **Coins**: Earn coins through AFK page and use them within the panel.
- **Servers**: Create, view, and edit servers.
- **User System**: Handle user authentication and password regeneration.
- **OAuth2**: Integrate with Discord for authentication.
- **Store**: Purchase resources using coins.
- **Dashboard**: View and manage resources and servers.
- **Admin**: Set, add, remove coins, and scan images & nodes.

# Why PalPod

**PalPod is the first Skyport Panel Dashboard, and it now even includes theming capabilities.**

# How to Install It

**To install the dashboard, you need the following requirements:**

- Node.js
- Discord Account
- Git

## First, Install Files

```sh
cd /etc
git clone https://github.com/mtq4/PalPod.git
cd PalPod
```

## Install Dependencies

```sh
npm install
```

## Rename the .env_example File to .env

```sh
mv .env_example .env
```

## Configure Everything Like Skyport URL AND APIKEY AND DISCORD OAUTH SETTINGS

```sh
nano .env
```

## Start PalPod

```sh
node index.js
```

## Additional Information

- **Support**: For any issues or support, please open an issue on the GitHub repository.
- **Contributing**: If you would like to contribute to PalPod, please fork the repository and submit a pull request with your changes.

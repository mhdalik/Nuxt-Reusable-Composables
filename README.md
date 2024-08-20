
# 🚀 Nuxt Reusable Composables Collection

A collection of reusable Nuxt.js composables to simplify development and avoid dependency headaches! This repository is designed to provide a range of ready-to-use utilities without the hassle of managing `node_modules`, version conflicts, or npm dependency management.

## 🌟 Why This Project?

In modern web development, managing dependencies can become tedious, with issues like version conflicts, deprecations, and the constant maintenance of `node_modules` folders. This repository aims to alleviate these pain points by offering a curated set of zero-dependency composables that can be directly used in your Nuxt.js projects.

No more waiting for npm installs, worrying about breaking changes, or dealing with messy dependency trees. Just copy the composables you need and focus on building your app!

## 📦 Features

- **Zero Dependencies**: Pure and clean composables with no external dependencies.
- **Plug-and-Play**: Simply copy and paste into your project—no installations needed.
- **Consistent API**: Each composable follows a consistent and easy-to-understand API.
- **Highly Reusable**: Optimized for reusability across different Nuxt.js projects.
- **Well-Documented**: Each composable is fully documented with usage examples.

## 🧩 Available Composables

Here’s a list of the currently available composables:

- **`useGeolocation`**: Manage geolocation and track user positions effortlessly.
- **`useLocalization`**: Handle localization and translations in your application.
- **`useFetchWrapper`**: Simplified fetch API wrapper with built-in error handling.

…and many more! Check out the [full list](./composables) of composables.

## 📖 Usage

Each composable can be easily integrated into your project. Here’s a quick guide:

1. **Copy the Composable**: Browse the repository and select the composable you want to use.
2. **Paste into Your Project**: Add the composable file to your project (e.g., `~/composables` directory).
3. **Use**: Use the composable wherever needed:

```vue
<script setup>
const { coords, error, isSupported } = useGeolocation()

if (isSupported) {
  console.log('Current coordinates:', coords)
} else {
  console.error('Geolocation is not supported:', error)
}
</script>
```

It’s as simple as that!

## 📚 Documentation

Each composable is fully documented in the `/docs` directory or you can check the inline comments within the code itself. The documentation includes:

- **Installation and Usage**: Step-by-step guide for each composable.
- **API Reference**: Detailed explanation of the parameters, return values, and more.
- **Examples**: Practical examples and use cases.

## 🛠️ Contributing

Contributions are welcome! If you have a useful composable that fits the goals of this repository, feel free to submit a pull request. Make sure to follow the contribution guidelines:

1. Fork the repository.
2. Create a new branch for your feature or fix.
3. Add your composable under the `/composables` directory.
4. Document your composable with usage examples and API reference.
5. Submit a pull request with a clear description.

Please refer to the [CONTRIBUTING.md](./CONTRIBUTING.md) file for more details.

## 💡 Philosophy

This repository follows a few key principles:

- **Simplicity**: Each composable is designed to be simple and straightforward.
- **Independence**: Composables are not tied to any npm packages or external dependencies.
- **Efficiency**: Minimize boilerplate and avoid reinventing the wheel.

By adhering to these principles, we aim to provide developers with reliable, easy-to-use utilities that streamline the development process.

## 🗒️ Roadmap

We plan to continue expanding this repository with more composables in areas like:

- State management
- Form validation
- API integrations
- UI utilities

If you have ideas or requests, feel free to open an issue.

## 🌐 License

This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details.

---

### Happy coding!




# Nuxt 3 Minimal Starter

Look at the [Nuxt 3 documentation](https://nuxt.com/docs/getting-started/introduction) to learn more.

## Setup

Make sure to install the dependencies:

```bash
# npm
npm install

# pnpm
pnpm install

# yarn
yarn install

# bun
bun install
```

## Development Server

Start the development server on `http://localhost:3000`:

```bash
# npm
npm run dev

# pnpm
pnpm run dev

# yarn
yarn dev

# bun
bun run dev
```

## Production

Build the application for production:

```bash
# npm
npm run build

# pnpm
pnpm run build

# yarn
yarn build

# bun
bun run build
```

Locally preview production build:

```bash
# npm
npm run preview

# pnpm
pnpm run preview

# yarn
yarn preview

# bun
bun run preview
```

Check out the [deployment documentation](https://nuxt.com/docs/getting-started/deployment) for more information.

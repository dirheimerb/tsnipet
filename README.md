# TSnippet: TypeScript Snippets for Visual Studio Code

[![GitHub tag](https://img.shields.io/github/tag/dirheimerb/tsnippet.svg?label=version)](1.0.0)

![TSnippet](./images/tslogo.jpeg)

## Overview

TSnippet is a Visual Studio Code extension designed to enhance the productivity of TypeScript developers. This extension provides a comprehensive set of snippets that cover various TypeScript features, making it easier to write clean and efficient TypeScript code. From basic structure definitions like interfaces and enums to advanced TypeScript utility types, TSnippet offers a wide range of tools to streamline your coding workflow.

## Features

- **Easy-to-use Snippets**: TSnippet includes a variety of snippets for creating TypeScript structures and utilities quickly. The snippets are designed to be intuitive and easy to remember, significantly reducing the time spent on boilerplate code.

- **Wide Range of Utilities**: Whether you're defining interfaces, modules, enums, or utilizing advanced TypeScript features like Utility Types (e.g., Awaited, Partial, Readonly), TSnippet has you covered.

- **Customizable Snippets**: Each snippet comes with placeholders that can be easily replaced with your specific code, allowing for a high level of customization while maintaining the efficiency of using snippets.

## Included Snippets

### Basic TypeScript Structures

- `typescript.interface`: Quickly create a TypeScript interface.
- `typescript.module`: Scaffold a TypeScript module.
- `typescript.enum`: Define a TypeScript enum with ease.

### TypeScript Utility Types

- `typescript.Awaited<T>`: Use the Awaited utility type.
- `typescript.Partial<T>`: Apply the Partial utility type.
- `typescript.Required<T>`: Utilize the Required utility type.
- `typescript.Readonly<T>`: Implement the Readonly utility type.
- `typescript.Record<K, T>`: Create a TypeScript Record.
- `typescript.Pick<T, K>`: Utilize the Pick utility type.
- `typescript.Omit<T, K>`: Employ the Omit utility type.
- `typescript.Exclude<T, K>`: Use the Exclude utility type.
- `typescript.Extract<T, K>`: Apply the Extract utility type.
- `typescript.NonNullable<T>`: Implement the NonNullable utility type.
- `typescript.Parameters<T>`: Use the Parameters utility type.
- `typescript.ConstructorParameters<T>`: Apply the ConstructorParameters utility type.
- `typescript.ReturnType<T>`: Utilize the ReturnType utility type.
- `typescript.InstanceType<T>`: Implement the InstanceType utility type.

`There are many more, this is just a selection.`

## Installation

1. Open Visual Studio Code.
2. Press `Ctrl+P` to open the Quick Open dialog.
3. Type `ext install tsnippet` to find the TSnippet extension.
4. Click on the install button to add TSnippet to your VS Code environment.

## Usage

Once installed, you can start using the snippets in any TypeScript file. Just type the prefix of the snippet (e.g., `tinter` for a TypeScript interface), and the corresponding code template will appear. You can then navigate through the placeholders to customize the snippet to your needs.

## Support and Contribution

For any issues, suggestions, or contributions, please visit the [TSnippet GitHub repository](https://github.com/dirheimerb/tsnippet). We welcome your feedback and contributions to make TSnippet even better for the TypeScript community.

## Release Notes

### 1.0.0

Initial release of TSnippet. Includes basic TypeScript snippets, as well as snippets for the most commonly used TypeScript utility types.
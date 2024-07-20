## Create a new project

`npx create-expo-app@latest`

## Start Developing

- To start the development server, run the following command:

  `npx expo start`

- To try your first change, Open the **app/(tabs)/index.tsx** file in your code editor and make a change.

```html
<ThemedView style="{styles.titleContainer}">
  <ThemedText type="title">Hello World!</ThemedText>
  <HelloWave />
</ThemedView>
<ThemedView style="{styles.stepContainer}"></ThemedView>
```

- Reset the Project, Time to MAKE your own app !

  `npm run reset-project`

  This command will move the existing files in **app** to **app-example** , then create a new **app** directory with a new **index.tsx** file.

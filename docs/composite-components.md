# Composite Components

In addition to creating primitive style components, Lab can be used to create multi-element composite components with the other style components in your library.

To create a composite component, click the _Add_ button in the upper right, then click the _Composite Component_ tab.

![library view](images/composite-library.png)

![composite component tab](images/composite-tab.png)

Next, in the _Imports_ field start typing the name of the components that you plan to use for creating the composite component. A list of available components will appear in the text below the form field.

**Note:** Lab currently only supports creating composite components with primitive style components and extended components; other composite components cannot be imported.

![composite component imports field](images/composite-imports.png)

Next, in the JSX editor, start using the imported components to build a composite component. To allow the values used in the composite component to be changed dynamically, use React [`props`][props].

Don't worry if the component isn't perfect at this step, you'll be able to edit it in the next step.

![composite component JSX field](images/composite-jsx.png)

Give your new component a unique name, then click the _Create Component_ button to add the component to your library and start editing it.

![composite component name field](images/composite-name.png)

To start, make sure you add an example in the _Examples_ editor to give your component some test content.

![composite component examples](images/composite-examples.png)

Since Lab components use [`styled-system`][system] you can adjust things like margin, padding and font-size for the components used in your composite component.

- Next: [Importing Components](importing.md)

[system]: https://github.com/jxnblk/styled-system
[props]: https://reactjs.org/docs/components-and-props.html

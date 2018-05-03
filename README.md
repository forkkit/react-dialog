# @crystallize/react-dialog

React component to display accessible dialogs

## Usage

```
yarn add @crystallize/react-dialog
```

**In your app root**

```
import { Wrapper } from '@crystallize/react-dialog';

export default () => (
  <main>
    <YourApp />
  </main>
  <Wrapper />
);
```

**Use it**

```
import { showDialog, showAlert, showConfirm } from '@crystallize/react-dialog';

await showDialog('Hey dude');
await showAlert('Wow');
await showConfirm('Are you sure?');
```

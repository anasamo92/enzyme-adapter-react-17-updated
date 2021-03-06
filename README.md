# enzyme-adapter-react-17-updated

Unofficial adapter for React 17 for [Enzyme]

## Installation

```
npm install --save-dev enzyme-adapter-react-17-updated
```

or, if you're using Yarn:

```
yarn add --dev enzyme-adapter-react-17-updated
```

### Note for npm v7 users

enzyme's dependencies have not yet been updated to declare React 17 in peerDependencies. You need to add `--legacy-peer-deps` to the install command for it to work correctly.

## Configuration

Finally, you need to configure enzyme to use the adapter you want it to use. To do this, you can use the top level `configure(...)` API.

```js
import Enzyme from 'enzyme';
import Adapter from 'enzyme-adapter-react-17-updated';

Enzyme.configure({ adapter: new Adapter() });
```

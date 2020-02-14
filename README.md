[![npm version](https://badge.fury.io/js/react-native-big-calendar.svg)](https://badge.fury.io/js/react-native-big-calendar)
[![Netlify Status](https://api.netlify.com/api/v1/badges/ca0f2cc8-bb4f-4a18-be48-c2b10e2b6046/deploy-status)](https://app.netlify.com/sites/react-native-big-calendar/deploys)

# react-native-big-calendar

Cross-platform gcal/outlook like calendar component for React Native.

[Components Demo](https://react-native-big-calendar.netlify.com/?path=/story/desktop--3days-mode)

# Features

- Cross Platform: Runs on the Web, iOS, Android with the power of React
- Type-safe: Fully written in TypeScript
- Customizable: Adjust styles of components
- Lightweight: ~15kb, only one dependency is `dayjs`

# Install

```
npm install --save react-native-big-calendar
```

Or if you use Yarn:

```
yarn add react-native-big-calendar
```

# Getting Started

```typescript
import { Calendar } from 'react-native-big-calendar'

const events = [
  {
    title: 'Meeting',
    start: new Date(2020, 1, 11, 10, 0),
    end: new Date(2020, 1, 11, 10, 30),
  },
  {
    title: 'Coffee break',
    start: new Date(2020, 1, 11, 15, 45),
    end: new Date(2020, 1, 11, 16, 30),
  },
]

function App() {
  return <Calendar events={events} height={600} />
}
```

# Documentation

See [Storybook](https://github.com/llotheo/react-native-big-calendar/blob/master/stories/index.stories.tsx)

# Screenshots

<img src="./assets/screenshot-desktop.png" height="500">
<img src="./assets/screenshot-mobile.png" height="500">

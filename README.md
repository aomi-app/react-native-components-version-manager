# react-native-component-version-manager

React Native Version Manager

### 快速上手

#### 获取App版本信息

```typescript
import { VersionManager } from '@aomi/react-native-components-version-manager';
import { Version } from './api';

async function getVersion() {
  const version: Version = VersionManager.get();
  console.log(version)
}
```

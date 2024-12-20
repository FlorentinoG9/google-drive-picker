# Google Drive Class Picker

this is a simple google drive picker built with a class based approach.
so you can use it in any javascript framework.

## Usage

```tsx
import type { GoogleConfig } from 'google-drive-class-picker'
import { GooglePickerLoader } from 'google-drive-class-picker'

function useGooglePicker(config?: GoogleConfig) {
  const picker = new GooglePickerLoader(clientId, developerKey, appId, config)

  return picker
}
```

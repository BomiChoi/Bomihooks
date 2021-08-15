# @bomihooks/use-title

React Hook to update your document's title<br>
Example
```javascript
import { UseTitle } from "@bomihooks/use-title";

export default function App() {
  const titleUpdater = UseTitle("Loading...");
  setTimeout(() => titleUpdater("Home"), 5000);
  return (
    <div className="App">
      <h1>Hello CodeSandbox</h1>
      <h2>Start editing to see some magic happen!</h2>
    </div>
  );
}
```
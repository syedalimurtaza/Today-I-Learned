functional component

```
const App = () => {
  return <div>{App.name}</div>;
};
```

class component

```
class App extends Component {
  render() {
    return <div>{this.constructor.name}</div>;
  }
}
```

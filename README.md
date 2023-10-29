# pg-custom-button

A custom component to render button

## Getting started

```bash
npm install pg-custom-button
```

```js
import CustomButton from 'pg-custom-button';

function App() {
	return (
		<CustomButton
			btnText="Submit"
			onPress={() => {
				alert('pressed');
			}}
			btnStyle={{
				backgroundColor: 'yellow'
			}}
			btnTextStyle={{
				color: 'purple'
			}}
		/>
	);
}
```

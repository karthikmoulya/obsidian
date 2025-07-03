React Native's Button is a simple component that renders a native-styled button. You can set a label, color, and an action when it's pressed.


Example

export default function ButtonExample(){
	const handlePress = () => {
		alert('Button was pressed!');
	}

	return (
		<View style={styles.container}></
	)
}
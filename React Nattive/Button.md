React Native's Button is a simple component that renders a native-styled button. You can set a label, color, and an action when it's pressed.


Example

export default function ButtonExample(){
	const handlePress = () => {
		alert('Button was pressed!');
	}

	return (
		<View style={styles.container}>
			<Text style={styles.title}>Press the Button</Text>
			 <Button title='Click Me' onPress={handlePress} />
		</View>
	)
}

const styles = StyleSheet.create({
  container: {
    flex: 1,
    paddingTop: 60,
    alignItems: 'center',
    backgroundColor: '#fff',
  },
  title: {
    fontSize: 24,
    marginBottom: 20,
  },
});
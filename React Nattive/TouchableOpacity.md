
- A pressable wrapper arond any element (View, Text, etc)
- Unlike Button, it gives you full control over style
- It also provides a fade (opacity) effect when tapped


 <View style={styles.container}>
      <TouchableOpacity style={styles.button} onPress={handlePress}>
        <Text style={styles.buttonText}>Tap Me</Text>
      </TouchableOpacity>
    </View>
- It' s a most basic container component in React Native
- Similar to div in web development
- Used to layout other components (like Text, Button, etc.)



Example
import React from 'react';
import { View, Text, StyleSheet } from 'react-native';

export default function ViewExample() {
  return (
    <View style={styles.container}>
      <Text style={styles.text}>This is inside a View!</Text>
    </View>
  );
}

const styles = StyleSheet.create({
  container: {
    flex: 1, // fills screen
    justifyContent: 'center',
    alignItems: 'center',
    backgroundColor: '#e0f7fa', // light blue background
  },
  text: {
    fontSize: 20,
    color: '#006064',
  },
});



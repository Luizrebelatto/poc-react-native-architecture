# Shadow Tree
- Structure representing layout components
- Architectural plan of the UI
- Uses Yoga to calculate layout

### Code Example
```javascript
<View>
  <Text>Hello</Text>
</View>
```

### Flowchart
![Shadow Tree Diagram](shadowTree.png)

### What is Shadow Node?
- Each component became shadow node
  - Properties
  - layout state
  - Yoga calculation result (width, height, position)
  - Parent/child relationships


# UML Design Tool

## Description

This UML Design Tool is a web-based application that allows users to create and manipulate UML class diagrams interactively. It provides a canvas interface where users can add classes, interfaces, properties, methods, and relationships between entities.

## Features

- Interactive canvas for creating UML diagrams
- Add and delete class/interface nodes
- Add properties and methods to nodes
- Delete individual properties and methods
- Create relationships between nodes with custom labels
- Drag and move nodes on the canvas
- Automatic resizing of nodes based on content
- Visual distinction between properties (regular font) and methods (italic font)

## Technologies Used

- HTML5 Canvas for rendering
- Vanilla JavaScript for functionality
- CSS for styling (minimal, as most rendering is done on canvas)

## How to Use

1. Open the application in a web browser.
2. Use the "Add Class" button to create a new class node on the canvas.
3. Click the "P" button on a node to add a property.
4. Click the "M" button on a node to add a method.
5. Use the "Add Relation" button to create relationships between nodes:
   - Click on the source node
   - Click on the target node
   - Enter the relationship type (e.g., extends, implements, uses)
6. Drag nodes to reposition them on the canvas.
7. Click the 'x' button on a node, property, or method to delete it.

## Code Structure

- `index.html`: The main HTML file that sets up the canvas and UI elements.
- `index.js`: The main JavaScript file containing the following classes:
  - `DesignTool`: Manages the overall application state and user interactions.
  - `ClassNode`: Represents a class or interface node in the UML diagram.
  - `Relation`: Represents a relationship between two nodes.

## Future Enhancements

- Save and load diagrams
- Export diagrams as images
- Undo/Redo functionality
- More UML diagram types (e.g., sequence diagrams, use case diagrams)
- Customizable styles for nodes and relationships

## About

For for information about me visit jameswallace.tech

# National Province to Province Navigation of China

A web application that generates optimal routes for traversing all connected provinces in China, starting from one province and ending at another.

## Features

- **Route Optimization**: Uses a "Nearest Neighbor" heuristic algorithm to find efficient paths through all connected Chinese provinces
- **Bilingual Interface**: Full support for both English and Chinese (中文) languages with a simple toggle switch
- **Province Selection**: Choose any starting and ending province from a comprehensive list
- **Visual Route Display**: Shows the complete path with clear visualization of visited provinces and transit points
- **Statistics**: Displays total moves and coverage percentage

## How It Works

1. Select a **Start Province** from the dropdown menu
2. Select an **End Province** from the dropdown menu
3. Click **Generate Route** to calculate the optimal path
4. View the route that visits all connected provinces in China

The algorithm ensures that:
- All connected provinces are visited at least once
- The route starts at your selected start province
- The route ends at your selected end province
- The path is optimized using the Nearest Neighbor heuristic

## Technical Details

- **Algorithm**: Greedy Nearest Neighbor with BFS for shortest path calculation
- **Graph Structure**: Bidirectional adjacency list representing province connections
- **Exclusions**: Taiwan (台) is excluded as per isolation rules
- **Technology**: Pure HTML, CSS, and JavaScript (no dependencies)

## Usage

Simply open `index.html` in any modern web browser. No installation or server setup required.


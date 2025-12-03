# Technical Context

## Technologies Used
- **Frontend Framework**: Angular (SmartMoving platform)
- **Styling**: CSS3 with custom properties
- **Platform**: SmartMoving customer portal system
- **Deployment**: CSS injection through platform admin interface

## Development Setup
- **Local Development**: Edit custom.css file
- **Preview**: Platform's built-in preview functionality
- **File Management**: Single CSS file for all customizations
- **Version Control**: Git for tracking changes

## Technical Constraints
1. **No HTML Access**: Cannot modify structure, only styling
2. **No JavaScript**: Cannot add interactivity or dynamic behavior
3. **CSS Specificity**: Must work within existing Angular component styles
4. **Platform Updates**: HTML structure may change with platform updates
5. **Cross-browser Compatibility**: Must work across modern browsers

## Dependencies
- SmartMoving platform (external dependency)
- Angular component class names (for CSS targeting)
- Company brand guidelines and colors

## Tool Usage Patterns
- **CSS Development**: Direct file editing with immediate preview
- **Debugging**: Browser developer tools for element inspection
- **Testing**: Visual testing across different screen sizes
- **Deployment**: Copy-paste CSS into platform admin interface

## Performance Considerations
- Minimal CSS to avoid slow loading
- Efficient selectors to reduce rendering time
- Optimized for mobile bandwidth
- No external resources or dependencies
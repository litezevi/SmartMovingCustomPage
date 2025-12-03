# System Patterns

## Architecture Overview
- **Platform**: SmartMoving customer portal (Angular-based)
- **Customization Method**: CSS injection through platform's custom CSS field
- **File Structure**: Single HTML file (source.html) + custom CSS file (custom.css)

## Source Code Paths
- `/source.html` - Platform-generated HTML structure (read-only reference)
- `/custom.css` - Custom CSS modifications (active development file)
- `/memoryBank/` - Project documentation and context

## Key Technical Decisions
1. **CSS-Only Approach**: Leveraging CSS specificity to override default styles
2. **Progressive Enhancement**: Making changes incrementally to avoid breaking functionality
3. **Mobile-First**: Ensuring responsive design works across all viewports
4. **Brand Integration**: Using company colors (#4630d2, #e1f5fe) consistently

## Design Patterns in Use
- **CSS Specificity Targeting**: Using Angular-generated class names for precise styling
- **Color System**: Primary (#4630d2), background (#e1f5fe), text (#000, #ffffff)
- **Typography Hierarchy**: Different font sizes and weights for information hierarchy
- **Component Styling**: Targeting specific sections (header, banner, info cards, tables)

## Critical Implementation Paths
1. Header section (app-header class)
2. Banner area (banner-flex, banner-info-container)
3. Information cards (your-info, customer-info, salesperson-info)
4. Tables and pricing sections (charges-table, app-table)
5. Action buttons (btn-custom-branding)

## Component Relationships
- Header contains branding and action buttons
- Banner shows estimate details and pricing
- Info cards display contact and location information
- Tables show detailed pricing and schedule
- All components share consistent color scheme and spacing
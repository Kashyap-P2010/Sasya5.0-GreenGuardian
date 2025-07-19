# Green Guardian

## Overview

Green Guardian is a Streamlit-based web application focused on environmental sustainability and eco-friendly practices. The application appears to be designed as an interactive dashboard that helps users track and visualize their environmental impact through various metrics and provides sustainability tips and guidance.

## User Preferences

Preferred communication style: Simple, everyday language.

## System Architecture

### Frontend Architecture
- **Framework**: Streamlit - A Python-based web framework for building interactive data applications
- **UI Components**: Custom CSS styling with environmental theme (green color palette)
- **Layout**: Wide layout with expandable sidebar for navigation
- **Visualization**: Dual visualization approach using both Matplotlib and Plotly for different chart types

### Backend Architecture
- **Runtime**: Python-based single-file application
- **Data Processing**: Pandas for data manipulation and analysis
- **Image Processing**: PIL (Python Imaging Library) for image creation and manipulation
- **Mathematical Operations**: NumPy for numerical computations

## Key Components

### 1. User Interface Layer
- **Custom Styling**: Environment-themed CSS with green gradients and nature-inspired colors
- **Responsive Design**: Wide layout configuration optimized for dashboard viewing
- **Interactive Elements**: Streamlit widgets for user interaction

### 2. Data Visualization Layer
- **Matplotlib Integration**: Traditional plotting for static visualizations
- **Plotly Integration**: Interactive charts and graphs for enhanced user experience
- **Custom Graphics**: PIL-based image generation for certificates or custom visuals

### 3. Data Processing Layer
- **Pandas DataFrames**: Core data structure for handling environmental metrics
- **NumPy Arrays**: Numerical computations for sustainability calculations
- **Base64 Encoding**: Image data encoding for web display

### 4. Scoring System
- **Environmental Score Display**: Custom-styled score presentation with gradient backgrounds
- **Real-time Calculations**: Dynamic scoring based on user inputs and environmental factors

## Data Flow

1. **User Input**: Users interact with Streamlit widgets to input environmental data
2. **Data Processing**: Pandas and NumPy process the input data for analysis
3. **Visualization Generation**: Matplotlib and Plotly create charts and graphs
4. **Score Calculation**: Environmental impact scores are calculated and displayed
5. **Tip Generation**: Contextual sustainability tips are provided based on user data
6. **Image Generation**: Custom images or certificates are created using PIL

## External Dependencies

### Core Libraries
- **streamlit**: Web application framework
- **matplotlib**: Static plotting library
- **plotly**: Interactive visualization library
- **pandas**: Data manipulation and analysis
- **PIL (Pillow)**: Image processing and generation
- **numpy**: Numerical computing

### Utility Libraries
- **base64**: Data encoding for web display
- **io**: Input/output operations for image handling

## Deployment Strategy

### Current Setup
- **Single-file Application**: Monolithic structure in `main.py`
- **Streamlit Server**: Built-in development server for local hosting
- **Static Assets**: CSS styling embedded within the application

### Scalability Considerations
- **Modular Refactoring**: Future growth may require splitting into multiple modules
- **Database Integration**: Currently appears to use in-memory data; may need persistent storage
- **API Integration**: Potential for external environmental data sources
- **Cloud Deployment**: Streamlit Cloud or containerized deployment options

### Performance Optimization
- **Client-side Caching**: Streamlit's built-in caching mechanisms
- **Image Optimization**: PIL-based image processing for efficient rendering
- **Interactive Charts**: Plotly for responsive user interactions without server round-trips

## Key Design Decisions

### Technology Stack Rationale
- **Streamlit Choice**: Rapid prototyping and deployment of data-driven applications
- **Dual Visualization**: Matplotlib for publication-quality static charts, Plotly for interactivity
- **PIL Integration**: Custom image generation for personalized environmental certificates

### User Experience Focus
- **Environmental Theme**: Consistent green color scheme reinforcing the sustainability message
- **Dashboard Layout**: Wide layout maximizing data visualization space
- **Interactive Elements**: Real-time feedback and dynamic content updates

### Data Architecture
- **In-memory Processing**: Suitable for current scale and real-time calculations
- **Flexible Visualization**: Multiple chart libraries for different presentation needs
- **Custom Styling**: Embedded CSS for branded user experience
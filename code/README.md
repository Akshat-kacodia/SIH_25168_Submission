## Tasks Accomplished  

- [x] **Data Collection:** Collected Sentinel-2 hyperspectral imagery (Indian Pines dataset for testing) and soil moisture sensor datasets.  
- [x] **Preprocessing & Alignment:** Cleaned hyperspectral bands, applied PCA/dimensionality reduction, and mapped sensor readings with GPS coordinates.  
- [x] **Feature Extraction:** Computed vegetation indices (NDVI, PRI, etc.), soil moisture indicators, and temporal patterns from IoT sensors.  
- [x] **Model Development:** Implemented CNNs for hyperspectral image classification and LSTMs for temporal soil/sensor trend analysis.   
- [x] **Dashboard Development:** Built a responsive web dashboard using Next.js, React, and Tailwind CSS for farmer-friendly access.  
- [x] **Visualization:** Added interactive maps, time-series plots, and anomaly alerts using Recharts.  
- [x] **Prototyping:** Developed an end-to-end pipeline demonstrating AI-powered early detection of crop stress, soil issues, and pest risks.  


## Next Steps / Future Work

- [ ] **Data Expansion:** Collect larger real-world hyperspectral and soil sensor datasets across diverse crops and regions.  
- [ ] **Model Optimization:** Fine-tune CNN and LSTM models, explore transformer-based architectures for improved accuracy.  
- [ ] **Real-time Integration:** Connect live IoT soil sensors with satellite imagery streams for continuous monitoring.  
- [ ] **Edge Deployment:** Optimize models for lightweight deployment on mobile/edge devices for on-field access.  
- [ ] **Advanced Analytics:** Incorporate pest/disease forecasting models and weather prediction into the platform.  
- [ ] **User Features:** Add farmer advisory system with zone-specific actionable insights and multilingual notifications.  
- [ ] **Validation:** Conduct pilot testing with agronomists and farmers to validate predictions and refine usability.  
  

## Technology Stack

This project leverages the following technologies:

- **[Next.js 14.2.16](https://nextjs.org):** For building a fast, scalable web app with routing and SSR.  
- **[React 18](https://react.dev):** Enables reusable components and smooth UI development.  
- **[TypeScript 5](https://www.typescriptlang.org):** Adds type safety and makes code easier to maintain.  
- **[Tailwind CSS 4.1.9](https://tailwindcss.com):** Utility-first CSS for quick, consistent styling.  
- **[Radix UI](https://www.radix-ui.com):** Accessible, unstyled primitives for custom components.  
- **[Recharts](https://recharts.org):** For clean, responsive charts and data visualizations.  
- **[Python](https://www.python.org):** Used for ML workflows, data preprocessing, and automation.  
- **[MATLAB](https://www.mathworks.com/products/matlab.html):** For numerical analysis and image processing.  
- **[MATLAB Hyperspectral Imaging Library](https://www.mathworks.com/help/images/hyperspectral.html):** For hyperspectral data analysis.  
- **[MATLAB Image Processing Toolbox](https://www.mathworks.com/products/image.html):** For segmentation, filtering, and image feature extraction.  
- **[MATLAB Deep Learning Toolbox](https://www.mathworks.com/products/deep-learning.html):** For model training with prebuilt architectures.  

## Key Features

- **Hyperspectral Image Analysis:** Automated preprocessing and extraction of key crop health indicators.  
- **AI-Powered Predictions:** Deep learning models to detect stress patterns and anomalies.  
- **Interactive Dashboard:** Real-time visualization with filters, maps, and charts for easy decision-making.  

## Local Setup Instructions (Windows & macOS) for [FRONTEND](https://github.com/Amnsngh0904/crop-health-dashboard) Repository

Follow these steps to run the project locally:


Before you begin, ensure you have the following installed on your system:

- **Node.js** (version 18.0 or higher)
  - Download from [nodejs.org](https://nodejs.org/)
  - Verify installation: `node --version`
- **pnpm** (recommended package manager)
  - Install globally: `npm install -g pnpm`
  - Verify installation: `pnpm --version`
- **Git** (for cloning the repository)
  - Download from [git-scm.com](https://git-scm.com/)

### Installation Steps

1. **Clone the Repository**
   
   git clone https://github.com/Amnsngh0904/crop-health-dashboard.git
   cd crop-health-dashboard

2. **Install Dependencies**
  
   pnpm install
   
3. **Start the Development Server**
   
   pnpm dev
   
4. **Open in Browser**
   - Navigate to [http://localhost:3000](http://localhost:3000)
   - The application should now be running locally

### Available Scripts

- `pnpm dev` - Start the development server
- `pnpm build` - Build the application for production
- `pnpm start` - Start the production server
- `pnpm lint` - Run ESLint to check for code issues


##  Local Setup & Installation for [BACKEND](https://github.com/mishra-bytes/FarmAssist) Repository

Follow the steps below to set up the project on your local system and run the MATLAB scripts.  

### 1. Prerequisites  
- Install **MATLAB R2021a or later** (earlier versions may work, but R2021a+ is recommended).  
- Ensure the following MATLAB toolboxes are installed:  
  - Image Processing Toolbox  
  - Deep Learning Toolbox  
  - Statistics and Machine Learning Toolbox

### 2. Clone the Repository  
git clone https://github.com/mishra-bytes/FarmAssist.git

cd FarmAssist

### 3. Running the Code  

1. Open **MATLAB** and set the current folder to the project directory (`FarmAssist`).  
2. Run the desired script from the MATLAB Command Window or Editor:  

   - **To train and test the CNN model**:  run('CNN.m')
   - **To train and test the Hybrid model**:  run('indian_pines_hybrid_cnn.m')

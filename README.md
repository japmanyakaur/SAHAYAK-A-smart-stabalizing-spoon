# SAHAYAK-A-smart-stabalizing-spoon

**SAHAYAK** is a smart assistive device designed to help individuals with hand tremors eat independently and live with dignity. It combines real-time motion correction (via stabilizing spoon hardware) with  tremor analysis system to deliver personalized medical insights.

“Because confidence and independence should never tremble.”

## Project Highlights

- Stabilizing Spoon Hardware: Real-time motion correction using gyroscope feedback
- Tremor Pattern Detection: ML model classifies tremor severity (Mild, Moderate, Severe)
- 4-Day Patient Progress Tracker: Analyzes tremor trends over multiple days
- Gyroscope-Based Data Collection: Captures x, y, z motion values over time
- Web Dashboard : Visual analysis and insights for caregivers and doctors

## Use Case

People with neurological conditions like Parkinson's, Essential Tremor, or Cerebral Palsy often struggle with routine tasks like eating. SAHAYAK enables:
- Autonomous eating through motion correction
- Tracking of hand tremor patterns over time
- Detection of worsening or improvement in tremor intensity

## How It Works

1. Sensor Data Capture  
   - Gyroscope collects real-time hand motion data (x, y, z)  
   - Data is logged and stored for daily review

2. Feature Extraction  
   - Variance, standard deviation, and custom features are calculated to represent tremor intensity

3. Tremor Severity Classification  
   - A trained Random Forest Classifier labels data as Mild, Moderate, or Severe

4. Patient Progress Visualization  
   - Line charts and frequency graphs reveal trends over 4 days  
   - Visual summary helps caregivers understand deterioration or recovery


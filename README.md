# **Whiteboard AI - Hand Gesture-Based Drawing and Problem Solving**

A Python project that uses a webcam for hand gesture recognition to draw on a virtual canvas and send the drawing to Google's Gemini AI for analysis or problem-solving.

## **Features**

- **Hand Gesture Detection**: Track hand movements via webcam using the `cvzone` library.
- **Real-Time Drawing**: Draw on a virtual whiteboard with your index finger.
- **AI Integration**: Send drawings to Google Gemini AI for analysis or solving math problems.
- **Streamlit Interface**: Simple web-based interface to interact with the canvas and display AI responses.

## **Result Samples
[2x33.webm](https://github.com/user-attachments/assets/09311872-e729-4000-a00a-8820bdf82283)

[2x.webm](https://github.com/user-attachments/assets/121f26e7-1d79-4aa5-9ce7-55bebafa5d8d)

[2x2.webm](https://github.com/user-attachments/assets/3f3adef9-9ff4-4608-9d65-1f6ab793bd18)



## **Setup**

1. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
2. Run the app:
   ```bash
   streamlit run main.py
   ```

## **Usage**

- **Index finger up**: Draw on the canvas.
- **All fingers up**: Clear the canvas.
- **Three middle fingers up**: Send the drawing to the AI for processing.

## **API Key**

Replace the placeholder in `main.py` with your Google API key:
```python
genai.configure(api_key="YOUR_API_KEY")
```

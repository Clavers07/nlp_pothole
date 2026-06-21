# NLP Pothole Detection

## Install

pip install -r requirements.txt

## Run

uvicorn main:app --reload

## API

POST /chat

Request:

{
    "message": "Apa itu YOLO?"
}

Response:

{
    "response": "YOLO (You Only Look Once) adalah algoritma object detection yang digunakan untuk mendeteksi jalan berlubang dengan cepat."
}
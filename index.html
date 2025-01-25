from flask import Flask, request, jsonify
import requests

app = Flask(__name__)

# LINE Messaging API credentials
LINE_CHANNEL_ACCESS_TOKEN = YOUR_CHANNEL_ACCESS_TOKEN
LINE_CHANNEL_SECRET = YOUR_CHANNEL_SECRET

# Mock data for available rooms
rooms = [
    {id 1, name Deluxe Room, price 1500},
    {id 2, name Suite Room, price 2500},
    {id 3, name Single Room, price 1000},
    {id 4, name Double Room, price 1800},
]

# Bookings list
bookings = []

# LINE webhook endpoint
@app.route(webhook, methods=[POST])
def webhook()
    body = request.get_json()

    if events not in body
        return OK, 200

    for event in body[events]
        if event[type] == message
            handle_message(event)

    return OK, 200

def handle_message(event)
    reply_token = event[replyToken]
    user_message = event[message][text].lower()

    if user_message == list rooms
        reply_rooms(reply_token)
    elif user_message.startswith(book room)
        reply_booking(reply_token, user_message)
    else
        reply_text(reply_token, Please send 'list rooms' to view available rooms or 'book room room_id' to make a booking.)

def reply_rooms(reply_token)
    room_list = Available Roomsn
    for room in rooms
        room_list += fID {room['id']}, Name {room['name']}, Price {room['price']}n

    reply_text(reply_token, room_list)

def reply_booking(reply_token, user_message)
    try
        _, room_id = user_message.split( )[1]
        room_id = int(room_id)
        room = next((room for room in rooms if room[id] == room_id), None)

        if not room
            reply_text(reply_token, Room not found. Please try again.)
        else
            bookings.append(room)
            reply_text(reply_token, fYou have successfully booked {room['name']}.)
    except Exception as e
        reply_text(reply_token, Invalid command. Please send 'book room room_id'.)

def reply_text(reply_token, text)
    headers = {
        Content-Type applicationjson,
        Authorization fBearer {LINE_CHANNEL_ACCESS_TOKEN}
    }
    payload = {
        replyToken reply_token,
        messages [
            {
                type text,
                text text
            }
        ]
    }

    requests.post(httpsapi.line.mev2botmessagereply, headers=headers, json=payload)

if __name__ == __main__
    app.run(debug=True)

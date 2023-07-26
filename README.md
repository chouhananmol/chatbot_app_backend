# chatbot_app_backend
# API - https://chatbot-app-backend.vercel.app/api
Post Request

## Body-
{
    "inputs": {
        "text": "what is 2+2 equals?"
    }
}

## Return -
{
    "generated_text": " Hi, how are you? I just got back from walking my dog. Do you have any pets?",
    "conversation": {
        "generated_responses": [
            " Hi, how are you? I just got back from walking my dog. Do you have any pets?"
        ],
        "past_user_inputs": [
            "Hello"
        ]
    }
}


#  or

## Body - Input - 
{
    "inputs": {  
        "generated_responses": [
            " Hi, how are you? I just got back from walking my dog. Do you have any pets?"
        ],
        "past_user_inputs": [
            "Hello"
        ],
        "text": "I Have a Dog"
    }
}

## Returns - 
{
    "generated_text": " What kind of dog do you have? I have a labrador retriever.",
    "conversation": {
        "generated_responses": [
            " Hi, how are you? I just got back from walking my dog. Do you have any pets?",
            " What kind of dog do you have? I have a labrador retriever."
        ],
        "past_user_inputs": [
            "Hello",
            "I Have a Dog"
        ]
    }
}

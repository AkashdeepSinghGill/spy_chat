from datetime import datetime

class Spy:

    def __init__(self, name, salutation, age, rating):
        self.name = name
        self.salutation = salutation
        self.age = age
        self.rating = rating
        self.is_online = True
        self.chats = []
        self.current_status_message = None


class ChatMessage:

    def __init__(self,message,sent_by_me):
        self.message = message
        self.time = datetime.now()
        self.sent_by_me = sent_by_me

spy = Spy('Akashdeep', 'Mr.', 20, 4.7)

friend_one = Spy('Vivek', 'Mr.',26,4.65)
friend_two = Spy('Harsh', 'Ms.',34,4.85)
friend_three = Spy('Sukhi', 'Mr.',31,5.0)


friends = [friend_one, friend_two, friend_three]


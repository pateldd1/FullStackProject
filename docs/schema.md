User:
has_many: bookings
has_many: hosted_homes
has_many: messages
validates username, password_digest, session_token

Homes:
	id, title, price, location, bedrooms, beds, bathrooms, guest_id, host_id
	ADD INDEX FOR EVERYTHING
	belongs_to :host—foreign-key: host_id
	belongs_to :guest— foreign-key: guest_id

Bookings:
	id, guest_id
	ADD INDEX FOR guest_id

Reviews:
	id, user_id, home_id, created_at
  ADD INDEX home_id
Messages:
  belongs_to sender and belongs_to receiver
  bonus
  sender_id
  receiver_id

  validates body

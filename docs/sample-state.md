{
  currentUser: {
    id: 1,
    username: "Devansh Patel"
  },
  forms: {
    signUp: {errors: []},
    logIn: {errors: []},
    createNote: {errors: ["body can't be blank"]}
  },
  homes: {
    1: {
      title: "Sample State",
      description: "is useful to plan",
      price: 500
      guest_id: 1,
      host_id: 1,
      bedrooms: 3,
      bathrooms: 3,
      beds: 2
    }
  },
  reviews: {
    1: {
      body: "Amazing Home!",
      user_id: 1,
      home_id: 1
    }
  }

  messages: {
    1: {
      body: "Have you seen this home?",
      sender_id: 1,
      received_id: 2
    }
  }

}

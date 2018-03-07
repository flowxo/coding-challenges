# Birthdays app challenge

The aim is to create a small web app that allows you to keep track of birthdays.

When you open the app, you'll be able to see whose birthdays are today, or coming up in the next 2 weeks. It will also tell you how old they are (or will be).

Important: Make sure you also view our [coding challenge guidelines](README.md).

## Main features

- A single UI page that shows you today's birthdays, upcoming birthdays (next 2 weeks), and a list view of all the people whose birthdays you're keeping track of.
- For today's birthdays and upcoming, show how old that person is (or will be).
- The list should show the person's name and date of birth.
- The ability to add a new birthday to the list, requiring the person's name and date of birth (add some validation).
- You should be able to delete birthdays too.

## Bonus features

If you have a little more time, add these extra bells and whistles to your app:

- Add a human friendly notation of when each person's birthday is to the list (3 days, 5 months, 6 weeks, etc.).
- A search option for the list, allowing you to filter by name.

## The technical requirements

- The UI should be a client side JavaScript app.
- You should use an API built in Node.js to store the data. There's no need to persist the data or use any kind of database, unless you want to.
- Use the data format below to initialise the app.
- Use any JavaScript frameworks you prefer. The only requirements are that you use Node.js for the server and JavaScript for the front-end.
- There should be tests for both the API and the JavaScript front end, use whatever testing frameworks/libraries you prefer. You don't need to provide thorough test coverage, but cover the basics well.

## Example data

```
[
  {
    "name": "John Doe",
    "birthday": "1981-08-02"
  },
  {
    "name": "Katie Smith",
    "birthday": "1973-05-20"
  },
  {
    "name": "Anna Jackson",
    "birthday": "1993-10-15"
  }
]
```

## Skills tested

- Client side JavaScript
- Server side JavaScript
- Structuring an API endpoint
- Designing a simple UI
- HTML/CSS

![Stack Builders](https://github.com/stackbuilders/nano-chat/raw/master/sb.png)

# Description

Yeah! A new [Stack Builders code challenge](https://www.stackbuilders.com/code-challenge)
is about to start and you're going to be part of it! In this repository you
will find the challenge description and some useful templates that will
save you some time and focus on the software architecture design.

We will evaluate your coding technique, your ability to work in a team and your communication skills.
Surprise us with your ideas and your creativity. You will be asked to present your work in front of
the public so be prepared to sell your ideas!

# The Challenge

## Banana Running

![logo][logo]

Banana Running is one of the top companies in time tracking software in sporting
events around the world. We are looking for a team of motivated professionals to
develop our training tracking app. Do you have what we need to make our vision come true?

### Our requirements

We want to track all of our customers’ training sessions. The user should
provide the following data:

- Description
- Date and time for the training session
- Running Track (set of coordinates)
- Total running distance
- Total running time

![form][form]

You decide how the user has to input the data and how to validate the input.
For instance, you can ask the user to enter the set of coordinates in a classic
form or use an embedded map in the page and ask the user to select points
from the map ([here][map-alternatives] are some alternatives to google maps if you want).

Also, we need to show the user his/her progress. We should at least present the following reports:

- **Running distance over time:** We’ll show the progress of the user’s running records.
You can add whatever fields you deem necessary (heart rate, burned calories, mean velocity) to make the report useful.

- **(Optional) Rank the user among others:** How the user is compared to other similar users?
Show him/her how to beat other people with similar running statistics.
You may have to extend your model in order to add user identification.

- **(Optional) Compare two running sessions:** The user would select two entries
from his history and will see the differences between them in terms of distance/time.
We can also show an animation of a simulated “race” between the two tracks

![compare][compare]

You have to decide the best way to present this information.
Make it user-friendly and interactive. When working on the frontend, add graphs,
interactive tables, maps, etc. Be mindful of the data you're going to persist
in the database and the API design when working on the back-end.

### Keys to success

- Be creative. For example, you can use a map to acquire the points of the
track and calculate the distance.

- You’ll decide on the architecture. Is it client/server? Server-side rendered?
Are you going with relational DBs or no-SQL? Bonus points for strong
architectural design, code cleanliness, and UX features.

- Auth is not needed for an MVP. Although you may add it along with audit
records and other features if your focus is on the backend rather than
the frontend.

- Think about extending the app in the future.

- Surprise us with features we didn’t think about!

## HTML Templates

We will provide a set of HTML pages with the front-end part of the exercise.
Additionally, if you want a static server we already set it up for you as well.
You just have to do the back-end part and replace the endpoints in the JS
files with your own. Please read the [templates/README](templates/README.md)
for more details.

# License

MIT, see the [LICENSE](LICENSE) file.

[logo]: ./img_repo/image1.png
[compare]: ./img_repo/image2.png
[form]: ./img_repo/image3.png
[map-alternatives]: https://geoawesomeness.com/google-maps-api-alternatives-best-cheap-affordable/

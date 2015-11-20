#Line Graph Plotter

Set up a webapp that plots a line graph

## Difficulty
  :star::star::small_orange_diamond::small_orange_diamond::small_orange_diamond:

## Description
- Given a list of comma separated numbers like: `1,2,3,5,8,13,21.5`
- We want to have a site to see the line graph of it easily, 
- for example, `http://myexample.com/?data=1,2,3,5,8,13,21.5` should return a page with a nice graph of the given data.


## Notes
  You can do this Rails, Python, Go, or Nodejs. *Please don't do php!*

## Specs
- It should raise 400 Bad Request, if params `data` is not present
- It should raise 400 Bad Request, if params `data` is not comma separated numbers
- It should be 200 Success if data is comma separated numbers. Ex: http://localhost:3000/?data=3,5,4,3,2.5
- It should plot a beautiful line graph with the given data as a series

## Bonus 
- Think of additional stuff to do

## Deliverables
- A live webapp, give us its address. You may host free apps on [Heroku](http://www.heroku.com)
- Its source code (github or zip)

## Submission
Drop an email to devops@deepo.io. Also include the name of your referrer if you had one =)


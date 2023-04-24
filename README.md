# ChatGPT Clone

<div align="center">

![ezgif-1-92e240a6d3](https://user-images.githubusercontent.com/22305274/220125119-ccbdb855-bdb9-476f-8f5f-f5d5530f0a24.gif)

</div>

This project is a ChatGPT clone that allows users to chat with an AI language model trained by OpenAI. It's powered by the github.com/orhanerday/OpenAI php library, which provides an easy-to-use interface for communicating with the OpenAI API.

![Image](https://user-images.githubusercontent.com/22305274/219878523-6d8be435-35df-4cce-b2cd-52334f9e7f12.png)

### Live Demo Video
<br>

https://user-images.githubusercontent.com/22305274/219877050-e5237734-4635-46f8-bf49-71a26356e0db.mp4

## GPT-4
Change model at `event-stream.php`
```php
....
$chat = $open_ai->chat([
    'model' => 'gpt-4',

....
```

## Using Docker
<hr>

> #### Method

#### Clone this repository to your local machine
```sh
git clone https://github.com/STARTIGER0120/ChatGPT.git
```
#### Navigate to the project directory
```sh
cd ChatGPT
```
#### Build the image
```shell
docker build -t chatgpt .
```
#### Run the app
```shell
docker run -p 8000:8000 -e OPENAI_API_KEY=sk-o7hL4nCDcjw chatgpt
```
#### Open your web browser and go

http://localhost:8000
<hr>



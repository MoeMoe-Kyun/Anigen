# Disclaimer
This project was done as an experiment to test it's feasibility. I disavow all uses of AI art generators that use a creator's work without permission.

# anigen
Hello, welcome to anigen. This is a deployable social media app which allows users to generate images of anime girls using various models from HuggingFace diffusers! To run, you should have mamba installed, or you can manually install the packages in requirements.txt using pip. I highly recommend using a virtual environment for this purpose.

After installing the required packages, you can initiate the project using the command:
```
flask --app anigen init-db
```
You can then run the application using:
```
flask --app anigen run --debug
```
for testing purposes. I will update this README.md in the future to cover deployment, as well as any other dependencies that are required.

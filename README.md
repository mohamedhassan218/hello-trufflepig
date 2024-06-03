# Quickstart with trufflepig

This repo contains a simple notebook that tries the [**trufflepig**](https://www.trufflepig.ai/) library with virtual data generated using AI.

**trufflepig** is a tool that allows users to upload their data as-is and make it searchable without the need for additional processing.


To use this do the following:
1. Clone the repository to your local machine:
   ```sh
   git clone git@github.com:mohamedhassan218/hello-trufflepig.git
   ```

2. Inside the directory, create your `.env` file and put in it a variable like the following:
   ```sh
   TRUFFLE_PIG_API_KEY=''
   ```

3. Get your API key (free but with limited amount of tokens per month) from [here](https://www.trufflepig.ai/account?page=apikeys) and put it in your `.env` file.


4. Now create your virtual environment and activate it:
    ```sh
    python -m venv .venv
    ```
    
    Activation differs:
    - For windows:
        ```sh
        .venv\Scripts\activate
        ```
    
    - For Unix or MacOS:
        ```bash
        source .venv/bin/activate
        ```

5. Install needed dependencies:
        
    ```sh
    pip install -r requirements.txt
    ```

6. Ensure that your notebook is connected to your `.venv` as a kernel and now you're ready to run the cells successfully.


**Feel free to take the code, customize it and use different file types and test it with this amazing library.**
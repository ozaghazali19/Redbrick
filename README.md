**Set Up Environment Variables:**

    - Copy `.env.example` to `.env`:

      ```bash
      cp .env.example .env
      ```

    - Obtain your `BEARER` and `TOKEN` values. These can typically be found in your browser’s local storage or session storage when you’re logged into the Redbrick platform. Look for keys related to authentication, such as `token` or `auth`.

    - Open `.env` and paste your values:

      ```env
      BEARER=your_bearer_token_here
      TOKEN=your_token_query_here
      ```

## Usage

1. **Run the Bot:**

    ```bash
    npm start
    ```

2. **Follow the Prompts:**

    - Choose between `Default Flow` or `Automatic Flow`.
    - In `Default Flow`, you can select actions like daily login, level-up, or task completion.
    - In `Automatic Flow`, tasks will be scheduled to run daily at midnight.

## Getting Your Tokens

1. **Local Storage:**
   - Open the [airdrop bot](https://t.me/rb_panda_bot/start?startapp=ref_GvHs8k).
   - Open your browser’s developer tools (usually F12 or right-click > Inspect).
   - Navigate to the **Application** tab.
   - Look for the **Local Storage** section.
   - Find and copy the value associated with keys like `token`, `auth`, etc.

2. **Session Storage:**
   - Similar to Local Storage, but check the **Session Storage** section in the **Application** tab.
# IYKYK - Telegram Integrated Pump Fun Bump Bot

## The community wanted some Pump.fun Solana fun so here we go.

I'll be testing this live in the [IYKYK Telegram group](https://t.me/IYKYK_Solana1).

I'll be optimising it for speed and efficency over the period of time before $IYKYK reaches Raydium

Here's the Pump.fun link: [https://pump.fun/5tzkqRo8XjHefzuJumij7suA6N7nTZA1FSLtzM8Bpump](https://pump.fun/5tzkqRo8XjHefzuJumij7suA6N7nTZA1FSLtzM8Bpump)

The two pump fun algorithms I'm testing are:-

## 1.

Start
  |
Initialize Logging & Client
  |
Retrieve Wallets from Database
  |
Create aiohttp Session
  |
While Transaction Count < Max Transactions
  |
For Each Wallet
  |
  Check Balance
  /        \
Insufficient  Sufficient
  Funds        |
              Execute Buy Trade
              |
              Execute Sell Trade
              |
  Increment Transaction Count
  |
End of Loop
  |
End

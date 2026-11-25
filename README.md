# PassGuard local prototype

1. Install Python 3.11 or newer.
2. Run `pip install -r requirements.txt`.
3. Run `python app.py`.
4. Open http://127.0.0.1:5000/register and create a lab account.
5. Log in and open the Simulation Lab.

This is an educational local prototype. It has in-memory login throttling, not production-grade distributed rate limiting, and does not yet implement MFA or ML. Synthetic events are generated without real attack traffic. Do not deploy this application publicly.

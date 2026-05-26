
  # Keel

  **Stop losing $200k/year to flaky tests.**

  Keel finds flaky tests, explains why they fail using AI, and opens the fix PR —
  automatically.

  - 🔍 Detects flaky tests across every CI run
  - 🤖 AI classifies root cause (race condition, time dependency, network issue)
  - 💰 Estimates annual dollar cost per test
  - 🔧 Opens auto-quarantine PR from keel-bot

  **Install in 5 minutes:**
  ```yaml
  - name: Report to Keel
    uses: trykeel/keel-action@v1
    if: always()
    with:
      api-key: ${{ secrets.KEEL_API_KEY }}

  Get started free → (https://trykeel.vercel.app)  

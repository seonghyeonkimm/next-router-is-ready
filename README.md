### How to reproduce bugs

- Open Safari Browser (Chrome is okay with this bug)
- Try to move to IdPage ([id].tsx) from HomePage (index.tsx)
- I expected router.isReady will be false, but router.isReady still is true.
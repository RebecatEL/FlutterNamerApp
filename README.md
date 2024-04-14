# namer_app

My first Flutter project following this tutorial:
- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)

## Live Demo

Live Demo deployed on [Vercel](https://flutter-namer-app.vercel.app/)

### Notes on deploying Flutter app on Vercel

1. In your Vercel project homepage, select the Git repo and click 'Import' button
2. In Configure Project page, under Build and Output Setting section, override below settings:
   - Build command: flutter/bin/flutter build web --release
   - Output directory: build/web
   - Install command: if cd flutter; then git pull && cd .. ; else git clone https://github.com/flutter/flutter.git; fi && ls && flutter/bin/flutter doctor && flutter/bin/flutter clean && flutter/bin/flutter config --enable-web
3. Click 'Deploy' button

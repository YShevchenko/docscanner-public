# DocScan — PDF Scanner & Document Tool

A privacy-first document scanner for Android built with Flutter.

## Features

- **Camera scanning** with native edge detection and perspective correction (via `cunning_document_scanner`)
- **On-device OCR** using Google MLKit — no data leaves your device
- **Image filters**: Original, B&W, Grayscale, Color Enhance
- **PDF export** — low / medium / high quality, no watermark
- **Full-text search** powered by SQLite FTS5
- **Document library** — grid/list view, sort by date or name, tag filtering
- **Dark mode** support

## Privacy

Zero backend. Zero tracking. No subscriptions. No ads. Paid upfront.
All scanned documents and extracted text stay on your device.

## Tech Stack

- Flutter 3.x
- `cunning_document_scanner` — native document scanning
- `google_mlkit_text_recognition` — on-device OCR
- `pdf` + `printing` — PDF generation
- `sqflite` with FTS5 virtual table — full-text search
- `provider` — state management
- `image` — filter pipeline

## Publisher

Heldig Lab — heldig.lab@pm.me

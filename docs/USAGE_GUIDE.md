# Luggage AI - Usage Guide

## How It Works
1. Upload a photo of your luggage
2. AI analyzes the contents
3. Get compliance report for airline regulations

## Supported Airlines
Check regulations for major carriers:
- Carry-on size limits
- Prohibited items detection
- Weight estimation

## API Integration
```typescript
const result = await analyzeLuggage(imageFile);
// Returns: { items: [], compliant: true, warnings: [] }
```

## Privacy
- Images processed locally when possible
- No data stored after analysis
- GDPR compliant

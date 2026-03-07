# UC Davis Medical Pathology Oral Histories Metadata

DAMS metadata for the Department of Medical Pathology Oral History Recordings (AR-133).

## Items

6 items, each with combined audio (MP3), transcript (PDF), and thumbnail (JPG):

| Item | Title | Notes |
|---|---|---|
| AR133_1_1 | Interview with Dr. Robert Cardiff | Audio: Tape 2 + Tape 1 (tapes were swapped) |
| AR133_1_3 | Interview with Dr. Murray Gardner | Audio: Tape 3 + Tape 4 |
| AR133_1_5 | Interview with Dr. George Lundberg | Audio: Tape 5 + Tape 6 |
| AR133_1_7 | Interview with Dr. Robert Stowell | Single tape |
| AR133_1_8 | Biography of Dr. Wilford Toreson | Audio: Tape 8 + Tape 9; text is a short biography |
| AR133_1_10 | Biography of Dr. Sefton Wellings | Audio: Tape 10 + Tape 11; text is a short biography |

## Structure

```
collection/
  medical-pathology-oral-histories.jsonld.json   # Collection metadata
  medical-pathology-oral-histories/
    labels.jsonld.json                           # Subject labels

items/
  AR133_1_1_J_Larkey_Dr_Robert_Cardiff.jsonld.json    # Item metadata
  AR133_1_1_J_Larkey_Dr_Robert_Cardiff/
    AR133_1_1_J_Larkey_Dr_Robert_Cardiff.jpg          # Thumbnail
    AR133_1_1_J_Larkey_Dr_Robert_Cardiff.mp3          # Audio (combined)
    AR133_1_1_J_Larkey_Dr_Robert_Cardiff.mp3.jsonld.json
    AR133_1_1_J_Larkey_Dr_Robert_Cardiff.pdf          # Transcript
    AR133_1_1_J_Larkey_Dr_Robert_Cardiff.pdf.jsonld.json
  ...
```

## Import

```bash
fin io import .
```

# EE 519 — HW1 Package (Notebooks 1–5)

This homework is a **hands-on DSP + speech** portfolio. You will complete **five Jupyter notebooks**.
📅 Deadline: Tuesday, February 3, 2026 -- 22:00 (10 PM).


## Folder structure (REQUIRED)

Keep this exact structure so grading is fast and reproducible:

```
HW1/
├── HW1_Notebook1_Recording_Sampling_Quantization.ipynb
├── HW1_Notebook2_Signal_Operations_and_System_Properties.ipynb
├── HW1_Notebook3_Time_Operations_Echo_Reversal.ipynb
├── HW1_Notebook4_Fourier_DFT_SpeechSpectra.ipynb
├── HW1_Notebook5_Speech_Production_Segmentation_Variability.ipynb
├── requirements.txt
└── audio/
    ├── x.wav                    # used by Notebooks 3 & 4 (sentence recommended)
    ├── x1.wav, x2.wav            # (optional) used by Notebook 2 if you prefer
    ├── speaker_self/
    │   ├── sent_1.wav
    │   ├── sent_2.wav
    │   ├── sent_3.wav
    │   ├── vowel_a.wav
    │   ├── vowel_i.wav
    │   ├── fric_s.wav
    │   └── fric_f.wav
    ├── speaker_2/
    │   └── sent_1.wav            # recommended (2nd speaker)
    └── speaker_3/                # optional
```

### Absolute paths are NOT allowed
- Do **not** use `/Users/...` or `C:\...` paths.
- Use only **relative paths** like `./audio/x.wav`.

## What to submit
Submit a single ZIP named:
- `HW1_<YourUSCID>.zip`

Your ZIP must contain the entire `HW1/` folder with notebooks and `audio/`.

## How we grade
Each notebook has its own rubric embedded at the top.
We grade:
- Correct execution (plots + listening evidence)
- Clear observations and reasoning
- Reproducibility (your notebook runs top-to-bottom after download)

## Environment
Install packages (if needed):
```bash
pip install -r requirements.txt
```

## Notes
- You may record audio externally (phone/laptop mic) and copy WAV files into `./audio/`.
- Some notebooks include **optional** in-notebook recording code, but external recording is always acceptable.
- If you use AI tools, complete the AI disclosure cell at the end of each notebook.

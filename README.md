Create a COMPLETE, SELF-TESTING Google Colab notebook (.ipynb) for Qwen3-TTS voice cloning using my voice sample.

SAVE THE NOTEBOOK AS:
Qwen3_Voice_Clone_Colab.ipynb

REFERENCE AUDIO:
https://archive.org/download/ppiirqpwrygv7ehggjvlaxcuz6fn8_w/pPiiRQpWrygV7ehgGjvl%2BaXcuz6fn8_w.mp3

OFFICIAL REFERENCES:
https://qwen.ai/blog?id=qwen3tts-0115
https://qwen.ai/blog?id=qwen3-tts-vc-voicedesign

CRITICAL EXECUTION RULES:
- Before FINALIZING the notebook, you must mentally simulate and validate EVERY cell.
- Assume the notebook will actually run in Google Colab.
- Every cell you create must be checked for:
  - syntax errors
  - import issues
  - dependency conflicts
  - CUDA issues
  - package incompatibility
  - missing files
  - incorrect model paths
  - runtime crashes
  - memory issues
  - invalid outputs
- If a cell could fail, modify the notebook logic immediately so it becomes resilient.
- Every cell must contain:
  - validation checks
  - try/except handling
  - logging
  - retry handling when possible
  - success/failure verification
- Every important cell must confirm:
  “✅ Cell executed successfully”
- If a cell generates output, verify the output actually exists before moving forward.
- If expected output is missing, automatically retry or repair logic.

AUTOMATED NOTEBOOK BEHAVIOR:
The notebook should:
1. Detect GPU automatically.
2. Verify CUDA availability.
3. Install all required packages.
4. Repair broken package installs automatically.
5. Handle pip dependency conflicts.
6. Install ffmpeg automatically if missing.
7. Download the reference voice automatically.
8. Verify the downloaded audio file is valid.
9. Convert audio format automatically if needed.
10. Load the latest supported Qwen3 voice cloning model.
11. Handle HuggingFace/model download issues automatically.
12. Retry failed model downloads.
13. Clear CUDA cache automatically when required.
14. Run a demo generation automatically.
15. Save generated audio automatically.
16. Verify generated audio file exists.
17. Display audio playback automatically in Colab.
18. Print detailed progress logs for every stage.

IMPORTANT:
- The notebook must NOT just contain code.
- It must behave like a self-testing pipeline.
- Each cell should internally validate its own success before the next stage.
- Add assertions/checks after critical operations.
- If generation fails, retry with fallback settings automatically.
- If GPU OOM occurs, reduce settings and retry automatically.
- If a package version fails, fallback to another compatible version automatically.

COLAB EXECUTION REQUIREMENTS:
- Make the notebook optimized specifically for Google Colab.
- Include automatic runtime environment checks.
- Include notebook restart handling after installations if necessary.
- Include safe re-import logic after runtime restart.
- Include compatibility handling for Python versions used in Colab.

VOICE CLONING REQUIREMENTS:
- Use ONLY my provided voice sample.
- Use latest Qwen3-TTS voice cloning workflow.
- Use high quality settings suitable for Colab GPU.
- Generate natural sounding speech.
- Add easy text editing section where I only change one variable:
  input_text = "..."

DEFAULT DEMO TEXT:
“Hello, this is a cloned voice generated using Qwen3 TTS on Google Colab.”

FINAL OUTPUT REQUIREMENTS:
- Save generated audio as:
  generated_output.wav
- Automatically verify the file exists.
- Automatically play audio inside Colab.
- Print final success confirmation:
  “✅ Voice cloning completed successfully”

VERY IMPORTANT FINAL RULE:
Before outputting the notebook, internally simulate running EVERY cell in order and verify:
- the cell would execute,
- expected outputs would appear,
- files would exist,
- and the notebook would complete successfully in Colab.

Return ONLY:
- The final production-ready notebook code/content.
- No explanations.
- No commentary.
- No partial snippets.
- No markdown explanation outside notebook structure.

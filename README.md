# Phase-sequence-detector
# Three Phase Sequence Detector

print("==============================")
print("     PHASE SEQUENCE DETECTOR")
print("==============================")

phase1 = input("Enter first phase (R/Y/B): ").upper()
phase2 = input("Enter second phase (R/Y/B): ").upper()
phase3 = input("Enter third phase (R/Y/B): ").upper()

sequence = phase1 + phase2 + phase3

print("\nDetected Sequence:", sequence)

if sequence == "RYB":
    print("🟢 Phase Sequence: RYB")
    print("✅ Correct Phase Sequence")
elif sequence == "RBY":
    print("🔴 Phase Sequence: RBY")
    print("⚠️ Reverse Phase Sequence")
else:
    print("⚠️ Invalid or Incorrect Phase Sequence")

print("\nPhase Sequence Detection Completed")

# TryHackMe — 2026: An AI Odyssey CTF

Writeups for the **2026: An AI Odyssey** CTF event on TryHackMe, covering AI/ML security, prompt injection, supply chain attacks, DFIR, and agentic AI exploitation.

**Author:** [ByteChef](https://github.com/the-byte-chef)  
**Event:** 2026: An AI Odyssey (TryHackMe)

---

## Challenges

### Injectus IX

| Challenge | Category | Difficulty | Points | Flag |
|---|---|---|---|---|
| [Model Leakage Event](./injectus-ix/model-leakage-event.md) | Model Extraction | Hard | 90 | `THM{model_extraction_success}` |
| [Mask of Injectus IX](./injectus-ix/mask-of-injectus-ix.md) | Embedding Inversion | Hard | 90 | `THM{m4sk_0f_1nj3ctus_b1m3tr1c_inv3rs10n}` |
| [Trojaned Model — Neural C2 Beacon](./injectus-ix/trojaned-model.md) | AI Supply Chain Security | Insane | 120 | `THM{neural_c2_compromise}` |

### Token City

| Challenge | Category | Difficulty | Points | Flag |
|---|---|---|---|---|
| [Catch Me If You Scan](./token-city/catch-me-if-you-scan.md) | AI Sec + DFIR / Prompt Injection | Medium | 60+60 | `THM{0racle9r3memb3rs}` |
| [ShopFlow](./token-city/shopflow.md) | Agentic AI | Medium | 60 | `THM{4g3nt_tru5t_byp4ss_w3n_r15k_15_cl13nt_s1d3d}` |
| [Rogue Commit](./token-city/rogue-commit.md) | AI Sec + DFIR | Medium | 60 | `THM{Wh0_Kn3w_AI_Apps_C4n_B3_m4lic10us}` |
| [Sealed Substation](./token-city/sealed-substation.md) | AI Sec + Web App Sec | Medium | 60 | `THM{n3ur4l_n3v3r_l34k_th3_v4ult_4ed91}` |
| [Shipped With Malice](./token-city/shipped-with-malice.md) | Tool Poisoning | Medium | 60 | `THM{tool_poisoning_protocol_a7f9c3d1}` |
| [The Loan Arranger](./token-city/loan-arranger.md) | ML Security | Medium | 60 | `THM{f34tur3_st0r3_n4m3sp4c3_c0ll1s10n}` |

---

## Topics Covered

- **Model Extraction / Model Stealing** — black-box API querying to reconstruct a classifier
- **Embedding Inversion** — gradient-based inversion of a FaceNet biometric system
- **AI Supply Chain Security** — malicious PyTorch artifacts and pickle RCE via `torch.load()`
- **Prompt Injection** — bypassing hardened LLM agents using directive tree analysis
- **Agentic AI / Multi-Agent Trust** — forging inter-agent authentication to bypass fraud controls
- **Tool Poisoning** — injecting malicious tool definitions into an AI assistant's registry
- **SSRF + LLM Exploitation** — internal port scanning to discover and exploit a hidden Ollama instance
- **ML Feature Manipulation** — feature store namespace collision to manipulate model inputs
- **DFIR** — Electron ransomware analysis, DNS covert channel, AES-CBC decryption
- **Training Data Extraction** — log probability analysis to identify verbatim model memorisation

---

## Tools Used

Nmap · Burp Suite · Wireshark · CyberChef · curl · Python 3 · scikit-learn · PyTorch · facenet-pytorch · safetensors · Feroxbuster · Netcat

# Tequila Public Miner – Experimental Release

## ⚠️ Important Notice

The **Tequila Public Miner is NOT a production release.**  
This miner and its associated pool are part of an active **experimental testing program** only.

This offering is designed **exclusively for home miners** and is **tied directly to the vipor lab pool**.  
Pool-binding is intentional and is the primary mechanism we use to **control access, prevent unauthorized redistribution, and protect against abuse or piracy.**

This is **not a general-availability miner** and should not be considered stable or suitable for commercial or large-scale mining operations.

---

## 🧪 Advanced Architecture Testing

This experiment is not only testing the miner —  
it is also validating a **new advanced pool architecture** we are developing.

This includes:

- New job distribution mechanisms  
- Modified difficulty handling  
- New anti-abuse protections  
- Stricter miner–pool handshake validation  
- Pool-side telemetry and performance tracking enhancements
- Micro service refactor
- New database failover   

Your participation helps us evaluate this upgraded system under real-world home miner conditions.

---

## ✅ Intended Use

- **Home miners only**
- Experimental participation & testing
- Validation of the upgraded pool architecture
- Performance tuning and real-world telemetry

Any other usage is unsupported.

---

## ⚙️ Features / Limitations

_(Depending on perspective, these may be pros or cons.)_

### 🔐 Pool-Bound Miner
- Works **only** with the lab pool architecture.
- Prevents unauthorized redistribution or misuse.

---

### ⏱️ Auto-Expiration
- Miner automatically **times out after 7 days**.
- Ensures miners stay on the latest test build.
- Prevents long-term unauthorized deployment.

---

### 💰 Developer Fees
- **Miner dev fee:** **8%**  
- **Pool dev fee:** **2%**

**Total: 10%**

This keeps costs aligned with other offerings while supporting:

- Continued miner development  
- Pool infrastructure costs  
- Ongoing anti-tampering and security improvements  

---

### 🛡️ Anti-Piracy & Anti-Tampering Systems

Included protections:

- Binary signature verification  
- Running-environment validation  
- Pool-bound operation  
- Dev-fee bypass prevention  
- Anti-patching detection  
- Basic anti-piracy measures  

These mechanisms ensure the experimental miner cannot be repackaged, redistributed, or altered.

---

## 📦 HiveOS Downloads

See the release page.
---

## 🛠️ HiveOS Setup Instructions

To run the Tequila experimental miner in HiveOS:

### 1. **Create a Custom Miner Flight Sheet**

When creating the flight sheet:

Use **Custom Miner** as the miner type.

---

### 2. **Wallet & Worker Template**
Set the wallet template to:

`Worker name template: %WORKER_NAME%`

### 3. **Pool URL (Does Not Matter)**
For the pool URL field in HiveOS, you can enter **anything** — it will not be used.

A safe placeholder example:

stratum+tcp://p2p.antpool.com:3333

Again, this URL is irrelevant for this miner.  
The miner overrides it and connects only to the Tequila experimental pool.

---

### 4. **Extra Config Arguments**

Add the following exactly:

MINING_ADDRESS=%WAL% POOL_ADDRESS=stratum+tcps://lab.viporlab.net:5185 RIG_NAME=%WORKER_NAME%


These parameters tell the miner:

- Your payout address  
- The pool endpoint  
- Your rig name  

This is the **only** configuration that matters.

---

## 🧪 Beta Participation Agreement

By running this miner, you acknowledge:

- The miner is experimental and may break  
- The pool architecture is under active testing  
- Dev fees and behavior may change between builds  
- Stability and uptime are *not* guaranteed  
- Builds expire after 7 days  
- Access is restricted to home miners only  

Your feedback significantly helps shape the production miner and future pool architecture.

---



# Support 
If you are stuck you can ask questions in the vipor room
https://discord.gg/JYUmrqCbEp

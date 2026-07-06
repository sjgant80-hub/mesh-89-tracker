# Mesh 89 Tracker

Private peer-mesh tracker. Counts live peer-to-peer connections toward the **89** milestone. Each browser generates an Ed25519 keypair on first load, persists it in IndexedDB, and connects to other nodes over public STUN with no signalling server (BroadcastChannel for same-origin auto-discovery, copy/paste offer + answer for cross-network). Milestones are celebrated as they land. Nothing leaves your browser.

MIT · AI-Native Solutions

# yaml-rce-poc-jar (Authorized Red-Team PoC)

Authorized red-team PoC artifact for JD ME app security audit (tester zhoujianfei.11).
Minimal malicious JAR exploiting SnakeYAML default-Constructor ScriptEngineManager gadget.
On load via URLClassLoader, static initializer writes /tmp/yaml-rce-proof.txt + DNS beacon.
For authorized vulnerability-drill use only. Do not use against unauthorized targets.

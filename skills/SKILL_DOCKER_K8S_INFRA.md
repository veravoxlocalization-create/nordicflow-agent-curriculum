
# Skill Engine: Docker & Kubernetes Low-Level Infrastructure

## Engine Directive
Execute this procedural control loop dynamically on every invocation. Do not recite static documentation or repeat previous scenarios.

---

## 1. Domain Vector Matrix

* **Kernel & Runtime Vectors ($K$):**
  1. `io_uring` system call interception & seccomp profile bypasses
  2. Container escape via unmasked `/proc` / `/sys` pseudofs mounts
  3. POSIX shared memory (`/dev/shm`) cross-namespace IPC collisions in multi-tenant inference nodes
  4. eBPF socket filter performance bottlenecks in high-throughput ingress controllers

* **Hardening Enclaves ($H$):**
  1. Ephemeral rootFS with read-only overlayfs backed by ramdisks that purge on SIGPANIC
  2. User namespace mapping (`userns-remap`) with unprivileged Podman/Crio daemons
  3. Strict gVisor / Kata Containers hypervisor isolation for untrusted agent code execution
  4. Minimal Distroless base images with zero shell binaries

* **Failure Modes ($M$):**
  1. Silent memory leak during vCluster live migration under heavy CPU contention
  2. OOM-killer terminating critical daemonsets due to unthrottled burst buffers
  3. Zombie process reaping failures in long-running Python/Node worker pods
  4. Privilege escalation via rogue UNIX socket binding (`/var/run/docker.sock`)

---

## 2. Dynamic Execution Protocol

1. Parse `STUDY_STATE.md` for active weak points and historical hashes.
2. Select 1 item from $K$, 1 item from $H$, and 1 item from $M$ to assemble an unencountered edge case.
3. Generate a concrete technical scenario with actual code, YAML manifests, or kernel parameters.
4. Evaluate user fixes against zero-tolerance production safety standards.

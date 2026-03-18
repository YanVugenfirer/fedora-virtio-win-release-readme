# VirtIO Windows Drivers — Fedora Project

This page describes where to find the **virtio-win** drivers for Windows guests on the Fedora project download site. These drivers enable Windows VMs to use paravirtualized (virtio) devices for disk, network, and other virtio devices when running on KVM/QEMU and other hypervisors.

---

## Download Locations

### 1. Latest stable release

The current stable release of virtio-win. The stable release is signed with Microsoft attestation signing.

**URL:** [https://fedorapeople.org/groups/virt/virtio-win/direct-downloads/stable-virtio/](https://fedorapeople.org/groups/virt/virtio-win/direct-downloads/stable-virtio/)

This directory contains the stable release artifacts (e.g. ISO, RPMs, MSI installers).

---

### 2. Latest release

This is the most recent virtio-win version publishedon Fedora Project.

**URL:** [https://fedorapeople.org/groups/virt/virtio-win/direct-downloads/latest-virtio/](https://fedorapeople.org/groups/virt/virtio-win/direct-downloads/latest-virtio/)

---

### 3. Archive of releases

Historical virtio-win releases. Use this to download a specific past version (e.g. for compatibility or reproducibility).

**URL:** [https://fedorapeople.org/groups/virt/virtio-win/direct-downloads/archive-virtio/](https://fedorapeople.org/groups/virt/virtio-win/direct-downloads/archive-virtio/)

Each subdirectory is named by version (e.g. `virtio-win-0.1.285-1/`, `virtio-win-0.1.271-1/`).

---

### 4. Upstream releases (unstable)

Pre-release and upstream builds. These are **not** stable; use only for testing or when you need features or fixes not yet in a stable release.

**URL:** [https://fedorapeople.org/groups/virt/virtio-win/direct-downloads/upstream-virtio/](https://fedorapeople.org/groups/virt/virtio-win/direct-downloads/upstream-virtio/)



---

## Summary

| Purpose                   | Location        | URL base                                                                 |
|---------------------------|-----------------|--------------------------------------------------------------------------|
| Latest stable             | Current release | `.../stable-virtio/`                               |
| Latest                    | Current release | `.../latest-virtio/`                               |
| Older or specific version | Archive         | `.../archive-virtio/`                                                    |
| Unstable / upstream       | Upstream        | `.../upstream-virtio/`                                                   |

For most users, the **latest stable release** directory is the right place to download the virtio-win ISO or installers.

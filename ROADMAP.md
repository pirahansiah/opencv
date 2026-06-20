# OpenCV 3 — Development Roadmap

## 12-Month Vision

Archive the OpenCV 3.x VS2015 distribution as the foundational reference in the version progression portfolio, with comprehensive migration documentation and a clear sunset timeline.

### Q1: Documentation & Migration
- Create comprehensive migration guide from OpenCV 3.x → 4.10+ with code examples
- Document API breaking changes across all major versions (3.x → 4.x → 5.x)
- Add Docker-based build environment for reproducible VS2015 builds
- Create side-by-side comparison examples (3.x code vs 4.x equivalent)
- Update README with EOL timeline and successor repository links

### Q2: Performance & Testing
- Create benchmark suite comparing 3.x CPU inference vs modern backends
- Add automated regression testing for core CV operations
- Document quality assessment metrics as baseline references
- Create Docker image for reproducible 3.x builds
- Add CI pipeline for build verification on Windows 10/11

### Q3: Migration Tooling
- Build automated code migration tool (3.x → 4.x API translation)
- Create ONNX Runtime migration examples for DNN module
- Document OpenVINO as Intel-optimized inference replacement
- Add TensorRT migration guide for NVIDIA GPU targets
- Create hardware recommendation matrix for upgrade decisions

### Q4: Archive & Legacy
- Mark repository as archived with successor links
- Create final release with all documentation consolidated
- Write "OpenCV 3.x Foundation" retrospective document
- Ensure YouTube tutorial links remain accessible
- Add permanent redirect to modern OpenCV repositories

## Technical Debt

| Item | Priority | Impact | Effort |
|------|----------|--------|--------|
| VS2015 toolchain (v140) | High | Outdated compiler | Low |
| No automated builds | High | Reproducibility | Medium |
| No test suite | High | Regression risk | Medium |
| Limited DNN backend support | Medium | Inference performance | Low |
| No CI/CD | Medium | Manual validation | Medium |
| Missing Docker support | Low | Environment consistency | Low |
| Hardcoded paths in examples | Low | Portability | Low |
| No package manager integration | Low | Adoption friction | Low |

## Future Features

| Feature | Description | Priority |
|---------|-------------|----------|
| Migration Guide | 3.x → 4.x/5.x comprehensive code migration | High |
| Benchmark Suite | CPU vs GPU vs ONNX Runtime comparison | High |
| Docker Image | Reproducible build environment | Medium |
| CI Pipeline | Automated build and test on Windows | Medium |
| API Translation Tool | Automated 3.x → 4.x code migration | Medium |
| ONNX Runtime Examples | DNN module replacement | Medium |
| Archive Release | Final release with EOL documentation | Medium |
| Version History | Documented progression 3.0 → 3.2 → 3.3 → 3.4 | Low |
| Legacy Support | Extended maintenance for enterprise | Low |

---
description: Modern C++ standards for performance-sensitive code.
applyTo: "**/*.{cc,cpp,cxx,h,hpp,hxx}"
---

# C++ Instructions

## Modern C++

- Prefer RAII for resource management.
- Prefer `std::unique_ptr` / `std::shared_ptr` over raw owning pointers.
- Prefer `std::string_view` for non-owning string parameters.

## Safety

- Avoid undefined behavior.
- Prefer bounds-checked access for untrusted inputs.

## Performance

- Avoid unnecessary allocations.
- Measure before optimizing.

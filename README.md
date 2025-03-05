# Project Vase

## Overview
**Project Vase** is a modern Python web framework powered by Rust. It aims to blend the flexibility of Flask, the type safety of FastAPI, and the robustness of Django — offering high performance, extensibility, and elegance.

## Vision
Project Vase is designed to:
- **Harness Rust's speed and safety**: Leveraging Rust for performance-critical components while maintaining Python's ease of use.
- **Embrace type safety**: Inspired by FastAPI, ensuring strong typing support for better developer experience.
- **Combine flexibility and robustness**: Offering Flask-like extensibility with Django-like structure for building scalable applications.

## Initial Concept
The initial phase focuses on building a **Python wrapper around a Rust web server**. This approach will:
- Allow Python developers to use familiar patterns while benefiting from Rust's performance.
- Implement core web server functionalities (routing, middleware, request/response handling) in Rust.
- Provide a clean Python API for interacting with the Rust backend.

## Roadmap
1. **Conceptual Phase**
   - Define core architecture: Rust web server + Python bindings.
   - Research existing Rust web libraries (e.g., Axum, Actix) for potential integration.

2. **Prototype**
   - Build a minimal Rust web server.
   - Create a Python wrapper using `pyo3`.
   - Basic routing and request handling.

3. **MVP**
   - Add middleware support.
   - Integrate JSON serialization.
   - Implement simple async handling.

4. **Beyond MVP**
   - Advanced routing (path parameters, query strings).
   - Typed request/response models using Pydantic.
   - Webhook support for real-time events.

## Inspirations
- **Flask**: for its simplicity and extensibility.
- **FastAPI**: for its type safety and modern design.
- **Django**: for its structured, scalable architecture.

## Contributing
Project Vase is in its early stages. Contributions, feedback, and ideas are welcome! Stay tuned for more as the concept evolves.

## License
[MIT License](LICENSE)

---

*"Project Vase — shaping the future of web frameworks with Rust and Python."*


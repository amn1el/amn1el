## `fn main() -> Amniel { ... }`

```rust
#[derive(Debug)]
struct BackendEngineer {
  languages: Vec<&'static str>,
  runtimes: Vec<&'static str>,
  databases: Vec<&'static str>,
  protocols: Vec<&'static str>,
  focus: String,
}

fn main() {
  let me = BackendEngineer {
    languages: vec!["Rust", "Go", "TypeScript", "Python"],
    runtimes: vec!["Node.js"],
    databases: vec!["SQLite", "PostgreSQL", "MongoDB"],
    protocols: vec!["gRPC", "Protobuf", "WebSockets"],
    focus: "High-performance Distributed Systems".to_string(),
  };
  println!("{:?}", me);
}
```

---

### Projects

Building at the intersection of web performance and systems-level safety.

- **[DevBench Workspace](https://github.com/amn1el/devbench)**
*High-performance JS playground. Tauri-based environment with custom Boa/SWC integration.*

- **[node-rs](https://github.com/amn1el/node-rs)**
*Native performance modules bridge between Node.js internals and Rust memory-safe ecosystem.*

- **[cloud.amniel.dev](https://github.com/amn1el/cloud.amniel.dev)**
*High-concurrency backend architecture. Built with Go/Fiber, utilizing a gRPC microservices gateway to delegate heavy multimedia processing and optimized database operations.*

---

### Technical Competencies

**Systems & Backend:** Rust, Go, Python, Node.js  
**Infrastructure & Tooling:** Tauri, SWC, Turborepo  
**Databases:** PostgreSQL, MongoDB, SQLite  
**Communication Patterns:** gRPC, Protobuf, WebSockets  
**System Architecture:** Distributed Systems, Low-latency API Design

---

### Operational Status

<div align="center">
  <a href="https://discord.com/users/604227193651986443">
    <img alt="my discord activity" src="https://lanyard.cnrad.dev/api/604227193651986443?bg=0d1117&showDisplayName=true&include_all_commits=true" />
  </a>
  <br/><br/><br/>
  <img src="https://wakatime.com/badge/user/972915bd-c915-4cf1-a2bd-2ba16ee5ef0a.svg" alt="WakaTime Stats" />
</div>


---

<div align="center">
  <em>"Converting caffeine and architectural panic into distributed systems since 2019."</em>
</div>

## Hi 👋, Welcome to Sudo's world!

[![Visits Badge](https://badges.pufler.dev/visits/sudopaeg/sudopaeg)](https://badges.pufler.dev)
[![Linkedin Badge](https://img.shields.io/badge/-JungHongKim-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/junghongkim/)](https://www.linkedin.com/in/junghongkim/)
[![Instagram Badge](https://img.shields.io/badge/-sudopaeg-dd2a7b?style=flat-square&logo=Instagram&logoColor=white&link=https://www.instagram.com/sudopaeg/)](https://www.instagram.com/sudopaeg/)
[![GitHub sudopaeg](https://img.shields.io/github/followers/sudopaeg?label=follow&style=social)](https://github.com/sudopaeg)
</br>

<code><img height="100" src="./assets/rustacean.png"></code>

```rust
use std::sync::{Arc, Mutex};
use std::thread;
pub struct SimpleHuman {
  fullname: &str,
  nickname: &str,
  from: Countries,
  languages: mut Vec<&str>,
  skillz: mut Vec<&str>,
  architectures: mut Vec<&str>
  currently_in: mut String,
}
// impls hidden :P
let jung = Arc::new(Mutex::new(SimpleHuman {
  fullname: "Jung Hong Kim",
  nickname: "sudo",
  from: Countries::SouthKorea,
  languages: vec!(["Korean", "English", "Mandarin", "TypeScript", "Rust", "Python", "Go", "C#"]),
  skillz: vec!(["React", "Recoil", "Node", "Kubernetes", "Docker", "AWS", "ElasticSearch", "Terraform", "Git", "Jira", "Xamarin"]),
  architectures: vec!(["microservices", "distributed inference", "design thinking", "event-driven"]),
  currently_in: String::from("Hong Kong 🇭🇰"),
}));
thread::spawn(move || awesome_life::update(Arc::clone(&jung)));
```

## Jung::beautify_aboutme()

- 🖥 I'm a full-stack developer, cloud architect and DevOps specialist
- 💼 Currently the founding member and CTO of [Dayta AI](https://dayta.ai)
- 🎓 Studied Bachelor of Computer Science and Bachelor of Business Administration at Hong Kong University of Science and Technology

## Jung::beautify_skillz()

### Backend

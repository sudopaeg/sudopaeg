## Hi 👋, Welcome to Sudo's world!

[![Visits Badge](https://badges.pufler.dev/visits/sudopaeg/sudopaeg)](https://badges.pufler.dev)
[![Linkedin Badge](https://img.shields.io/badge/-JungHongKim-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/junghongkim/)](https://www.linkedin.com/in/junghongkim/)
[![Instagram Badge](https://img.shields.io/badge/-sudopaeg-dd2a7b?style=flat-square&logo=Instagram&logoColor=white&link=https://www.instagram.com/sudopaeg/)](https://www.instagram.com/sudopaeg/)
[![GitHub sudopaeg](https://img.shields.io/github/followers/sudopaeg?label=follow&style=social)](https://github.com/sudopaeg)
</br>

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
thread::spawn(move || awesome_life::random_update(Arc::clone(&jung)));
```

## Jung::beautify_aboutme()

- 🖥 I'm a full-stack developer, cloud architect and DevOps specialist
- 💼 Currently the founding member and CTO of [Dayta AI](https://dayta.ai)
- 🎓 Studied Bachelor of Computer Science and Bachelor of Business Administration at Hong Kong University of Science and Technology
- 🤖 Interest areas include Artificial Intelligence, Cloud Computing, Sustainable and Affordable Technology for Innovation!

## Jung::beautify_skillz()

### Frontend

<p>
  <img height="40" src="./assets/javascript.png" alt="JavaScript">
  <img height="40" src="./assets/typescript.png" alt="TypeScript">
  <img height="40" src="./assets/react.webp" alt="React.js">
  <img height="40" src="./assets/wasm.png" alt="WebAssembly">
</p>

### Backend

<p>
  <img height="40" src="./assets/node.png" alt="Node.js">
  <img height="40" src="./assets/python.png" alt="Python">
  <img height="40" src="./assets/rust.png" alt="Rust">
</p>

### DevOps

<p>
  <img height="40" src="./assets/docker.png" alt="Docker">
  <img height="40" src="./assets/kubernetes.png" alt="Kubernetes">
  <img height="40" src="./assets/terraform.png" alt="Terraform">
  <img height="40" src="./assets/jira.png" alt="Jira">
  <img height="40" src="./assets/git.png" alt="Git">
  <img height="40" src="./assets/elasticsearch.png" alt="Elasticsearch">
</p>

### Cloud & Networking

<p>
  <img height="40" src="./assets/aws.png" alt="AWS">
  <img height="40" src="./assets/nginx.png" alt="Nginx">
  <img height="40" src="./assets/traefik.png" alt="Traefik">
</p>

## Jung::fetch_stats()

![sudopaeg's github stats](https://github-readme-stats.vercel.app/api?username=sudopaeg&count_private=true)

<!--START_SECTION:activity-->
<!--END_SECTION:activity-->

<div align="center">
  <h1>👋 Hello, World!</h1>

  <!-- 个人简介 -->
  <h3>💻 <code>profile.rs</code></h3>
  ```rust
  #[derive(Debug, Clone)]
  struct ArchitectProfile {
      id: &'static str,
      role: Role,
      state: State,
      mission: &'static str,
  }

  #[derive(Debug, Clone)]
  enum Role {
      /// ☢️ 核废料工程师
      NuclearWasteDev,
      /// 🏗️ 架构师预备役
      ArchitectReserve,
  }

  #[derive(Debug, Clone)]
  enum State {
      Transmuting {
          from: &'static str,
          to: &'static str,
          method: Strategy,
      },
      Refactoring,
      Debugging,
  }

  #[derive(Debug, Clone)]
  enum Strategy {
      DDD,    // 领域驱动设计
      CQRS,   // 命令查询职责分离
      EventSourcing, // 事件溯源
  }

  impl ArchitectProfile {
      fn new() -> Self {
          ArchitectProfile {
              id: "GuLuGuLu3399",
              role: Role::ArchitectReserve,
              state: State::Transmuting {
                  from: "Spaghetti Code (Vue3/Java)",
                  to: "Clean Architecture (Rust/Go)",
                  method: Strategy::DDD,
              },
              mission: "在紫荆桥下写的 BUG，终将成为勋章",
          }
      }
  }

  fn main() {
      let me = ArchitectProfile::new();
      println!("{:?}", me);
  }
  ```

  <!-- 技术栈 -->
  <h3>🎨 <code>tech_stack.yml</code></h3>
  <p align="center">
    <img src="https://skillicons.dev/icons?i=rust,go,java,python,vue,ts,vite,tauri,mysql,redis,docker,k8s&theme=dark&perline=6" alt="技术栈" />
  </p>

  <!-- 重构路线图 -->
  <h3>🚧 <code>refactor_roadmap.mmd</code></h3>
  ```mermaid
  graph LR
      subgraph LEGACY [🔴 技术债务]
          A[Vue3 组件地狱] --> B[Spring 单体应用]
          B --> C[重启大法<br/>内存泄漏]
      end

      subgraph IN_PROGRESS [🟡 重构中]
          C -->|Rust 类型安全| D[微服务核心]
          B -->|Go 并发模型| E[高性能网关]
          A -->|Vue3 组合式 API| F[模块化前端]
      end

      subgraph FUTURE [🟢 规划中]
          D --> G[事件驱动架构]
          E --> H[服务网格]
          F --> I[微前端架构]
      end

      style LEGACY fill:#3a1c1c,stroke:#ff6b6b,stroke-width:2px,color:#fff
      style IN_PROGRESS fill:#3a2c1c,stroke:#ffd166,stroke-width:2px,color:#fff
      style FUTURE fill:#1c3a2c,stroke:#06d6a0,stroke-width:2px,color:#fff
  ```

  <!-- 项目展示 -->
  <h3>📦 <code>projects.md</code></h3>
  <table>
    <thead>
      <tr>
        <th>项目</th>
        <th>技术栈</th>
        <th>状态</th>
        <th>描述</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td><b>Bifrost CMS</b></td>
        <td>Rust • Go • gRPC</td>
        <td>🟢 活跃开发</td>
        <td>高性能无头内容管理系统</td>
      </tr>
      <tr>
        <td><b>Animal Husbandry</b></td>
        <td>Java • Spring Boot</td>
        <td>🟡 维护中</td>
        <td>畜牧业智能管理平台</td>
      </tr>
      <tr>
        <td><b>Personal Blog</b></td>
        <td>Gin • Tauri • Vue3</td>
        <td>🟢 活跃</td>
        <td>个人技术博客与知识库</td>
      </tr>
      <tr>
        <td><b>Web-Work</b></td>
        <td>Vue3 • TypeScript • Go</td>
        <td>🟡 开发中</td>
        <td>全栈学习与算法可视化平台</td>
      </tr>
    </tbody>
  </table>

  <!-- GitHub 数据统计 -->
  <h3>📊 <code>github_stats.json</code></h3>
  <p align="center">
    <img src="https://github-readme-stats.vercel.app/api?username=GuLuGuLu3399&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="GitHub Stats" height="165" />
    <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=GuLuGuLu3399&layout=compact&theme=tokyonight&hide_border=true&langs_count=6" alt="Top Languages" height="165" />
  </p>

  <!-- 联系信息 -->
  <h3>📬 <code>contact_info.toml</code></h3>
  ```toml
  [contact]
  email = "gulugulu3399@example.com"
  github = "https://github.com/GuLuGuLu3399"
  blog = "https://blog.example.com"

  [interests]
  tech = ["分布式系统", "编译器设计", "数据库内核"]
  hobbies = ["骑行", "摄影", "开源贡献"]
  ```

  <p align="center">
    <i>"代码是写给人看的，机器只是顺便执行"</i>
  </p>

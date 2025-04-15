# **Fish the AI frind**

**Fish** is a lightweight, powerful command-line interface for interacting with **Jellyfish AI**, designed for developers, researchers, and AI enthusiasts. Whether you're asking quick questions, managing chat sessions, training on custom data, or running complex tasks, `fish` provides a smooth and intuitive interface for working with your AI assistant. Built with clarity and speed in mind, it offers a modular command structure, streamlined flags, and support for scripting and automation. Dive into the future of AI interaction — with Fish.

## 🧠 Updated Fish CLI Command Set

| Command        | Description                                                                 |
|----------------|-----------------------------------------------------------------------------|
| `fish init`    | Initialize a Jellyfish project or workspace                                 |
| `fish ask`     | Send a quick question to Jellyfish AI (stateless or contextual)             |
| `fish chat`    | Start, resume, or manage conversational memory sessions                     |
| `fish learn`   | Teach Jellyfish something new (structured memory or skill upload)           |
| `fish remember`| Store or view persistent memory chunks (`facts`, `skills`, `notes`)         |
| `fish script`  | Run a `.fish` script (Fish ML program or pipeline)                          |
| `fish model`   | List, inspect, or manage available learning models                          |
| `fish train`   | Train a custom model using `.fishml` or dataset                             |
| `fish log`     | Inspect past sessions, prompts, and events                                  |
| `fish run`     | Run a task or command defined in a `.fish` script                           |
| `fish config`  | Configure settings and profiles                                             |
| `fish status`  | System and model runtime status                                             |
| `fish update`  | Update CLI or sync with Jellyfish backend                                   |
| `fish version` | Show installed version and build info                                       |
| `fish help`    | Display help for any command                                                |

---

### 📁 `.fish` and `.fishml` Files

| Extension     | Purpose                                         |
|---------------|-------------------------------------------------|
| `.fish`       | Fish ML script (AI workflow, task, or routine)  |
| `.fishml`     | Model training file (dataset + model hints)     |
| `.fishmem`    | Memory pack (structured persistent memory)      |

---

### 🔧 Example Commands

```bash
# Ask a quick question
fish ask "How do I implement a trie in C?"

# Start a memory-aware chat session
fish chat --new --remember

# Teach the AI something new
fish learn --file ./concepts.fishmem --tag algorithms

# Save a fact into memory
fish remember add "The Eiffel Tower is 300m tall." --tag facts

# View all remembered facts
fish remember list --tag facts

# Run a custom AI script
fish script run ./auto_summary.fish --input notes.txt

# Train a fine-tuned model
fish train --dataset ./coding-tips.fishml --from jelly-base --name dev-buddy

# Show available models
fish model list

# Show the system's current state
fish status
```

---

### 🧠 Philosophy

The `fish` CLI isn't just a wrapper — it’s a **learning interface**. Everything from commands to memory to scripts feeds into Jellyfish's evolving intelligence. You’re not just giving instructions; you’re **shaping your AI’s mind**.

## **Prerequisites**

Ensure you have the following installed before starting:

- **Meson Build System**: This project relies on Meson. For installation instructions, visit the official [Meson website](https://mesonbuild.com/Getting-meson.html).

## **Setting Up Meson Build**

1. **Install Meson**:
    - Follow the installation guide on the [Meson website](https://mesonbuild.com/Getting-meson.html) for your operating system.

## **Setting Up, Compiling, Installing, and Running the Project**

1. **Clone the Repository**:

    ```sh
    git clone https://github.com/fossillogic/fossil-app.git
    cd fossil-app
    ```

2. **Configure the Build**:

    ```sh
    meson setup builddir
    ```

3. **Compile the Project**:

    ```sh
    meson compile -C builddir
    ```

4. **Install the Project**:

    ```sh
    meson install -C builddir
    ```

5. **Run the Project**:

    ```sh
    fish
    ```

## **Contributing**

Interested in contributing? Please open pull requests or create issues on the [GitHub repository](https://github.com/fossillogic/fish).

## **Feedback and Support**

For issues, questions, or feedback, open an issue on the [GitHub repository](https://github.com/fossillogic/fish/issues).

## **License**

This project is licensed under the [Mozilla Public License](LICENSE).

# **Jellyfish AI**

Jellyfish AI is a cold, deterministic, and manipulation-resistant AI framework designed for model creation, reasoning, and data management without ideology, emotion, or social influence. Its CLI tool, fish, allows users to build, manage, and run AI modules and datasets while maintaining strict auditability, persistence, and operational integrity.

## **Prerequisites**

Ensure you have the following installed before starting:

- **Meson Build System**: This project relies on Meson. For installation instructions, visit the official [Meson website](https://mesonbuild.com/Getting-meson.html).

## **Setting Up Meson Build**

1. **Install Meson**:
    - Follow the installation guide on the [Meson website](https://mesonbuild.com/Getting-meson.html) for your operating system.

## **Setting Up, Compiling, Installing, and Running the Project**

1. **Clone the Repository**:

    ```sh
    git clone https://github.com/fossillogic/fish.git
    cd fish
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

Interested in contributing? Please open pull requests or create issues on the [GitHub repository](https://github.com/fossillogic/app-c).

## **Feedback and Support**

For issues, questions, or feedback, open an issue on the [GitHub repository](https://github.com/fossillogic/app-c/issues).

## **License**

This project is licensed under the [Apache 2.0 License](LICENSE).

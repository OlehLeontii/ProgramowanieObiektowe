<p align="center">
<a href="https://preactjs.com" target="_blank">
	


<p style="text-align:center;" ><img src="https://mcgtn.org/storage/logos/library-logo.png" alt="Logo" width="400" height="400"></p>

</a>
</p>
<p style="font-size: 30px" align="center">Projekt <b>Biblioteka</b></p>

**Wizualnej:**

1. Okno logowania

2.	Okno rejestracji
3.	Okono katalog książek
4.	Okno moje rezerwacje
5. Profil użytkownika (dane osobowe oraz rezerwacje) 
- Transparent asynchronous rendering with a pluggable scheduler
- **Instant production-grade app setup with [Preact CLI](https://github.com/preactjs/preact-cli)**






You can find some awesome libraries in the [awesome-preact list](https://github.com/preactjs/awesome-preact) :sunglasses:

---

## Getting Started

> 💁 _**Note:** You [don't need ES2015 to use Preact](https://github.com/developit/preact-in-es3)... but give it a try!_

The easiest way to get started with Preact is to use [Preact CLI](https://github.com/preactjs/preact-cli). This simple command-line tool wraps up the best possible tooling for you, and even keeps things like Webpack and Babel up-to-date as they change. Best of all, it's easy to understand! Start a project or compile for production in a single command (`preact build`), with no configuration needed and best practices baked in! 🙌

#### Tutorial: Building UI with Preact

With Preact, you create user interfaces by assembling trees of components and elements. Components are functions or classes that return a description of what their tree should output. These descriptions are typically written in [JSX](https://facebook.github.io/jsx/) (shown underneath), or [HTM](https://github.com/developit/htm) which leverages standard JavaScript Tagged Templates. Both syntaxes can express trees of elements with "props" (similar to HTML attributes) and children.

To get started using Preact, first look at the render() function. This function accepts a tree description and creates the structure described. Next, it appends this structure to a parent DOM element provided as the second argument. Future calls to render() will reuse the existing tree and update it in-place in the DOM. Internally, render() will calculate the difference from previous outputted structures in an attempt to perform as few DOM operations as possible.




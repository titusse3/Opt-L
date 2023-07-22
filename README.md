
<h1 align="center">
  <br>
  <a href="https://github.com/titusse3/Opt-L"><img src="https://github.com/titusse3/Opt-L/assets/61415485/5257d387-e902-47a0-99a1-eb9a279d0d00" alt="Optl" width="200"></a>
  <br>
  Opt-L
  <br>
</h1>

<h4 align="center">A compact and efficient software module that simplifies the handling of command-line options in C programs like the linux option. Offering developers an easy way to incorporate customizable and flexible behaviors into their applications. </h4>

<p align="center">
  <a href="#key-features">Key Features</a> •
  <a href="#how-to-use">How To Use</a> •
  <a href="#credits">Credits</a> •
  <a href="#related">Related</a> •
  <a href="#license">License</a>
</p>

<div style="display:flex;justify-content:center;">
  <img src="https://github.com/titusse3/Opt-L/assets/61415485/15bd9b31-c9ac-40a6-9019-38cbf95ad14b"/>
</div>

## Key Features

* A list of custom return statut that describe the the option traitment.
* Built-in ```help``` option you can custom.
  > **Note** 
  > This option if is entered, will interup the traitment of the possible other option. Not regarding the position of it.
* An environement variable is available too.
* Possibility to creat option that stop the program the module is use for.
* There is an indicator that specify the traitment of the next argument to not be possibly considered as an option.
  > **Note**
  > The default value for it is ```--```, but can be change on the interface of the module.
* Option can be represented like descried below :
  
  | Short representation | Long representation |
  | :---: | :---: |
  | Beging by the character ```-```, is defined by a single character. |  Beging by the sequence ```--```, is defined by a sequence of characters. |
 

* Short and long option can need argument.
  > **Note**
  > For the short one, the separator between the option and the argument must be 
  > space. In contrary, for the long one, the separator can be change on the interface. By default,
  > is value is ```=```.
* For the short option, you can call them by joining their short representation.
  Just like below :
   
  > **Example**
  > ```-ivh``` will be equivalent to the call of ```-i -v -h``` (where ```i``` and 
  > ```v``` represente a short option).

* For the long one, you can call an option by calling a non ambiguous prefix of 
  it (a prefix is ambiguous if he is a prefix of at least two option). Example just below : 

  > **Example** 
  > ```--help``` is equivalent to the call ```--h```, ```--he```, ```--hel``` is there 
  > isn't any option that have ```h```, ```he``` or ```hel``` for prefixe.

## How To Use

To use this module you'll have to clone this project and them use it has mutch has you want 😁.

## Emailware

Opt-L is an [emailware](https://en.wiktionary.org/wiki/emailware). Meaning, if you liked using this app or it has helped you in any way, we'd like you send us an email at <theo.renauxv@gmail.com> or <Lurgrid@gmail.com> about anything you'd want to say about this software.

## Credits

The readme of this project was made using a template from [Markdownify](https://github.com/amitmerchant1990/electron-markdownify).

## Related

Ressource use to make this module :
- [GNU](https://tldp.org/LDP/abs/html/standard-options.html) "Standard" option.
- [POSIX](https://www.gnu.org/software/libc/manual/html_node/Argument-Syntax.html) Option descriptions.

## You may also like...

[Lnid](https://github.com/Lurgrid/Lines-Identical) - An identical line finder between/in file(s) that use this module for his option.

## License

MIT

---

> GitHub [@titusse3](https://github.com/titusse3) &nbsp;&middot;&nbsp;
> GitHub [@Lurgrid](https://github.com/Lurgrid) &nbsp;&middot;&nbsp;

# DynAlloy Analyzer

DynAlloy is an extension of the formal specification language [Alloy](https://alloytools.org). Alloy is a relatively popular formal specification language because of various reasons, including:
- it has simple formal semantics, based on relations
- its syntax is simple, with a few constructs (with intuitive meaning)
- its specifications follow an OO-like style
- it is designed with fully automated analysis support in mind

Alloy is suitable for specifying static structural properties of systems, but is less adequate for the specification of dynamic properties of systems, i.e., properties regarding executions. **DynAlloy extends Alloy by incorporating the notion of action to better describe state change and properties of state changing situations.** An example is available in this [tutorial](https://github.com/gregistecco/dynalloy/wiki).

## Download

Last release:
[Download](https://github.com/gregistecco/dynalloy/releases)

## Run

`$ java -jar dynalloy.jar`

java 1.8 required

---

##### [Tutorial](https://github.com/gregistecco/dynalloy/wiki)

##### [Sample Models](https://github.com/gregistecco/dynalloy/tree/master/Sample%20Models)

##### [New debbuger-like trace visualization](https://github.com/gregistecco/dynalloy/wiki)

---

### Actual Colaborators

- César Cornejo
- Germán Regis
- Nazareno Aguirre
- Marcelo Frias

### Publications

-  [DynAlloy analyzer: a tool for the specification and analysis of alloy models with dynamic behaviour.](https://dl.acm.org/doi/10.1145/3106237.3122826)
Regis, G.; Cornejo, C.; Brida, S. G.; Politano, M.; Raverta, F.; Ponzio, P.; Aguirre, N.; Galeotti, J. P.; and Frias, M. F.
In Bodden, E.; Schäfer, W.; van Deursen, A.; and Zisman, A., editor(s), Proceedings of the 2017 11th Joint Meeting on Foundations of Software Engineering, ESEC/FSE 2017, Paderborn, Germany, September 4-8, 2017, pages 969–973, 2017. ACM

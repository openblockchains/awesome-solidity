# Awesome Solidity (Contract) Programming Language & Tools


## What's News?

For weekly solidity (contract) programming "dev stuff" updates - see [**NEWS »**](NEWS.md)


Bonus: For weekly ethereum improvement proposal (eip) updates - see [**ETHEREUM »**](ETHEREUM.md)



## New to Solidity?

_Official_

Solidity Language @ <https://soliditylang.org>

- Read the Docs @ <https://docs.soliditylang.org/en/latest/>
- Blog @  <https://blog.soliditylang.org>
- Forum @ <https://forum.soliditylang.org>
- Source @ <https://github.com/ethereum/solidity>

<!-- break -->

_More_

Solidity by Example @ <https://solidity-by-example.org>

Learn X in Y Minutes (Where X=Solidity) @ <https://learnxinyminutes.com/docs/solidity>



## Alternative Contract-Oriented Programming Languages

###  Higher-Level

**Fe** - the syntax is inspired by Python and Rust. It is easy to learn, even for those who have never dealt with the ethereum virtual machine (evm) before; designed to be safe and equipped with the tooling needed to validate contracts; uses the same intermediate language as Solidity (YUL), making it a great choice not only for the ethereum mainnet, but also for (upcoming) layer two chains.

- web @ <https://fe-lang.org>
- docs @ <https://fe-lang.org/docs>
- source @ <https://github.com/ethereum/fe>

**Vyper** - a more recently developed language, similar to Serpent and again with Python-like syntax. 
Intended to get closer to a pure-functional Python-like language than Serpent, but not to replace Serpent.

- docs @ <https://vyper.readthedocs.io>
- source @ <https://github.com/vyperlang>

**Secure Ruby / Small, Smart, Secure, Safe, Solid & Sound (S6) Ruby (sruby / s6 ruby)** - the ruby programming language for contract / transaction scripts on the blockchain world cmputer - yes, it's just ruby; see the [**red paper »**](https://github.com/s6ruby/redpaper)

- source @ <https://github.com/s6ruby>
- talks  
  - Code Your Own (Crypto Blockchain) Contracts w/ Ruby (sruby), Universum & Co @ <https://github.com/geraldb/talks/blob/master/contracts.md> 


<!-- break -->

_Historic_

**Serpent** - a procedural (imperative) programming language with a syntax similar to Python. Can also be used to write functional (declarative) code, though it is not entirely free of side effects.

- source @ <https://github.com/ethereum/serpent>

**Bamboo** - a language influenced by Erlang, with explicit state transitions and without iterative flows (loops). Intended to reduce side effects and increase auditability. 

- source @ <https://github.com/pirapira/bamboo>


###  Low-Level ("Assembly-Like")

**YUL** - official "intermediate" assembly language for the ethereum virtual machine (evm)


> Yul (previously also called JULIA or IULIA) is an intermediate language that can be compiled to bytecode for different backends.
>
> It can be used in stand-alone mode and for "inline assembly" inside Solidity. 
> The compiler uses Yul as an intermediate language in the IR-based code generator 
> ("new codegen" or "IR-based codegen"). 
> Yul is a good target for high-level optimisation stages that can benefit all target platforms equally.

- docs @ <https://docs.soliditylang.org/en/latest/yul.html>


**Huff** - a low level "itermediate" assembly language for the ethereum virtual machine (evm)

-  web @ <https://huff.sh>
-  docs @ <https://docs.huff.sh>
- source @ <https://github.com/huff-language>


_Historic_

**Low-level Lisp-like Language / Lisp Like Language (LLL)** - a functional (declarative) programming language, with Lisp-like syntax. It was the first "itermediate" assembly language for ethereum contracts.

- docs @ <https://lll-docs.readthedocs.io>



### More / Misc

**Cairo** - a STARK-based turing-complete language for writing provable programs on blockchain.

- web @ <https://www.cairo-lang.org>
- docs @ <https://www.cairo-lang.org/docs>
- source @  <https://github.com/starkware-libs/cairo-lang>




## Contract (Source Code) Verfication Tools & Services

### Sourcify

> Sourcify enables transparent and human-readable smart contract interactions through automated Solidity contract verification, 
> contract metadata, and NatSpec comments.

- web @ <https://sourcify.dev>
- docs @ <https://docs.sourcify.dev>
- source @ <https://github.com/ethereum/sourcify>



### Etherscan Verify (& Publish Contract Source Code)

- docs @ <https://etherscan.io/verifyContract>


### Codeslaw  (Verified Contract Search) 

> Codeslaw is a code search engine for verified contracts on ethereum and beyond 
> to help developers find and learn from verified and live contracts.
> Verified  contracts come from the following sources:
> 1) Etherscan, 2) Tin Tin's Contract Sanctuary, 3) Sourcify

- web @ <https://www.codeslaw.app>




## Application Binary Interface (ABI) Specs, Tests, Tools & Services


### (Method) Signature Databases / Lookups




## More Awesome Awesomeness

_A curated list of more awesome lists._


- [**Awesome Solidity**](https://github.com/bkrem/awesome-solidity) by Ben Kremer  - a sorted a-to-z lists of soldity goodies



## Meta

**License**

![](https://publicdomainworks.github.io/buttons/zero88x31.png)

The awesome list is dedicated to the public domain. Use it as you please with no restrictions whatsoever.

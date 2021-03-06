AVPASS
======

AVPASS is a tool for leaking the detection model of Android malware detection systems (i.e., antivirus software), and bypassing their detection logics by using the leaked information coupled with APK obfuscation techniques. AVPASS is not limited to detection features used by detection systems, and can also infer detection rules so that it can disguise any Android malware as a benign application by automatically transforming the APK binary. To prevent leakage of the application logic during transformation, AVPASS provides an Imitation Mode that allows malware developers to safely query curious detection features without sending the entire binary.

AVPASS offers several useful features to transform any Android malware so it can bypass anti-virus software. Below are the main features AVPASS offers:

- APK obfuscation with more than 10 modules
- Feature inference for the detection system by using individual obfuscation
- Rule inference of the detection system by using the 2k factorial experiment
- Targeted obfuscation to bypass a specific detection system
- Safe query support by using Imitation Mode

DEMO
----

* Bypassing API-, Dataflow-, Interaction-based detection systems

[![DEMO1](http://img.youtube.com/vi/6D1miTSRKA8/0.jpg)](http://www.youtube.com/watch?v=6D1miTSRKA8)


* Inferring and Bypassing AVs through VirusTotal

[![DEMO2](http://img.youtube.com/vi/GkMyobbyl88/0.jpg)](http://www.youtube.com/watch?v=GkMyobbyl88)

License
-------

This project is released under the [GPL license](./LICENSE).


Running & Docs
--------------

More documentation is available in [docs/README.md](docs/README.md).


Authors and Contact
-------------------

These are the list of contributors for implementing AVPASS:

- Jinho Jung
- Chanil Jeon
- Max Wolotsky
- Insu Yun

Send us email for any questions. 

Main contact point: Jinho Jung (jinho.jung@gatech.edu)


Contribute
----------

If you want to contribute, please pick up something from our [Github issues](https://github.com/sslab-gatech/avpass/issues).

Cite
----
- Black Hat USA 2017

```
@inproceedings{jung:avpass-bh,
  title        = {{AVPASS: Leaking and Bypassing Antivirus Detection Model Automatically (to appear)}},
  author       = {Jinho Jung and Chanil Jeon and Max Wolotsky and Insu Yun and Taesoo Kim},
  booktitle    = {Black Hat USA Briefings (Black Hat USA)},
  month        = jul,
  year         = 2017,
  address      = {Las Vegas, NV},
}
```

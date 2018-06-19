=========
CHANGELOG
=========

2.0.4
=====

* Fix output_data_dir to reference an existing directory.
* Fix error message.
* Make pip install verbose. 

2.0.3
=====

* Fix error class for user script errors.
* Adding Readme.

2.0.2
=====

* Improve logging
* Support for hyperparameters with JSON serialized and non serialized keys altogether
* Training Environment transforms to env vars
* Created beta framework entrypoint
* Filter SageMaker provided hyperparameters and user provided hyperparameters
* Script mode
* Cache module installation
* Support to requirements.txt
* Decoder/Encoder support for numpy, JSON, and CSV

1.0.4
=====

* bug: Configuration: Change module names to string in __all__
* bug: Environment: handle hyperparameter injected by tuning jobs

1.0.3
=====

* bug: Training: Move processing of requirements file out to the specific container.

1.0.2
=====

* feature: TrainingEnvironment: read new environment variable for job name

1.0.1
=====

* feature: Documentation: add descriptive README

1.0.0
=====

* Initial commit

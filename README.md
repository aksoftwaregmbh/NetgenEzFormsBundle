NetgenEzFormsBundle
===================

[![Build Status](https://img.shields.io/travis/netgen/NetgenEzFormsBundle.svg?style=flat-square)](https://travis-ci.org/netgen/NetgenEzFormsBundle)
[![Code Coverage](https://img.shields.io/codecov/c/github/netgen/NetgenEzFormsBundle.svg?style=flat-square)](https://codecov.io/gh/netgen/NetgenEzFormsBundle)
[![Downloads](https://img.shields.io/packagist/dt/netgen/ez-forms-bundle.svg?style=flat-square)](https://packagist.org/packages/netgen/ez-forms-bundle)
[![Latest stable](https://img.shields.io/packagist/v/netgen/ez-forms-bundle.svg?style=flat-square)](https://packagist.org/packages/netgen/ez-forms-bundle)
[![License](https://img.shields.io/packagist/l/netgen/ez-forms-bundle.svg?style=flat-square)](https://packagist.org/packages/netgen/ez-forms-bundle)

Integration of Symfony's Form component with eZ Publish 5 Public API

Currently implemented forms:

| Entity / Form             | Create | Update | Information collection
| ------------- | --- | --- | ---
| Content      | yes | yes | yes
| User      | yes | yes | no

Currently supported FieldTypes:

| FieldType             | Supported
| ------------- | ---
| Author         | no
| BinaryFile     | yes
| Checkbox       | yes
| Country        | yes
| Date           | yes
| DateAndTime    | yes
| EmailAddress   | yes
| Float          | yes
| Integer        | yes
| Image          | yes
| ISBN           | yes
| Keyword        | no
| Media          | no
| MapLocation    | yes
| Page           | no
| Rating         | no
| Relation       | yes
| RelationList   | no
| RichText       | no
| Selection      | yes
| TextBlock      | yes
| TextLine       | yes
| Time           | yes
| Url            | yes
| User           | yes
| XmlText        | no

## Documentation
Please check [Petar's blog post](http://www.netgenlabs.com/Blog/Creating-and-updating-eZ-Publish-Content-via-Symfony-s-Form-component).

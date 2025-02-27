# Certiface

Biblioteca Certiface para iOS.

## Instalação

O SDK está disponível via [CocoaPods](https://cocoapods.org/) (forma recomendada), mas também pode ser instalado manualmente.

### CocoaPods

1. No início do `Podfile`, inclua a linha:
```rb
source 'https://github.com/oititec/liveness-ios-specs.git'
```
2. Após isso, adicione a dependência:
```rb
pod 'FaceCaptcha', '~> 3.1.1'
```
3. Rode `pod install`.

### Manual

Para adicionar o SDK manualmente no seu projeto, siga estas [instruções](Documentation/ManualInstallation.md).

## Uso

### Permissões de acesso

 No `Info.plist` do projeto, adicione a descrição de uso de câmera (`Privacy - Camera Usage Description`):

![Instalação 4](Documentation/Images/installation_4.png)

### Liveness FaceCaptcha

As instruções de uso e integração do Liveness FaceCaptcha podem ser acessadas [neste link](Documentation/FaceCaptcha-Usage.md).



### Liveness 3D

As instruções de uso e integração do Liveness 3D podem ser acessadas neste link.



### Documentoscopia

As instruções de uso e integração da Documentoscopia podem ser acessadas [neste link](Documentation/Documentscopy-Usage.md).

## Sample

Um exemplo de implementação pode ser encontrado no projeto [SampleFaceCaptcha](https://github.com/oititec/liveness-ios-sdk/tree/main/SampleFaceCaptcha "SampleFaceCaptcha"), neste mesmo repositório.

## Documentação Auxiliar

- [Troubleshooting](Documentation/Troubleshooting.md)

## Changelog

- As novidades das versões podem ser acessadas [neste link](Documentation/Changelog.md).

## Guias de migração

- [3.0.0](Documentation/Migration-Guide-3.0.0.md) - BREAKING CHANGE
- [2.0.0](Documentation/Migration-Guide-2.0.0.md) - BREAKING CHANGE
- [1.2.0](Documentation/Migration-Guide-1.2.0.md) - BREAKING CHANGE

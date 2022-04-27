## Blazor SignaturePad component

English | [中文](README.zh.CN.md)



### Demo

https://www.blazor.zone/signaturepads

https://blazor.app1.es/signaturepad

## Instructions:

1. NuGet install pack 

    `BootstrapBlazor.OnScreenKeyboard`

2. _Imports.razor or Razor page

   ```
   @using BootstrapBlazor.Components
   ```
3. Razor page

    ```
        <SignaturePad OnResult="((e) =>  Result=e)" />
    ```
    ```
        <SignaturePad OnResult="((e) =>  Result=e)" BtnCssClass="btn btn-outline-success" />
    ```
    ```
        <SignaturePad OnResult="((e) =>  Result=e)"
                      SignAboveLabel="Sign above"
                      UndoBtnTitle="Undo"
                      SaveBase64BtnTitle="OK"
                      ChangeColorBtnTitle="Change color"
                      ClearBtnTitle="Clear" />
    ```

    ```
    @code{

        /// <summary>
        /// 签名Base64
        /// </summary>
        public string? Result { get; set; }

    }
    ```

4.  More informations

    Bootstrap style Blazor UI component library
Based on the Bootstrap style library, it is carefully built, and 100 a variety of commonly used components have been added to bring you an extraordinary feeling for rapid development projects

    <https://www.blazor.zone>

    <https://www.blazor.zone/signaturepads>

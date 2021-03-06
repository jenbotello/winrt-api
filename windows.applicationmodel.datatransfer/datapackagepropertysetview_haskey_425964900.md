---
-api-id: M:Windows.ApplicationModel.DataTransfer.DataPackagePropertySetView.HasKey(System.String)
-api-type: winrt method
---

<!-- Method syntax
public bool HasKey(System.String key)
-->

# Windows.ApplicationModel.DataTransfer.DataPackagePropertySetView.HasKey

## -description
Indicates whether the [DataPackagePropertySetView](datapackagepropertysetview.md) object contains a specific property.

## -parameters
### -param key
The key.

## -returns
True if the property set has an item with the specified key; otherwise false.

## -remarks
With the [DataPackagePropertySetView](datapackagepropertysetview.md) class, use **HasKey** as a way to see whether the object contains a specific property. This is useful in situations where your app requires a custom property that the [DataPackagePropertySetView](datapackagepropertysetview.md) object doesn't directly support. For more info, see [IMapView(String, Object)](../windows.foundation.collections/imapview_2.md).

## -examples

## -see-also

# vendor_apps_MiuiCamera

# Add code in device.mk

$(call inherit-product-if-exists, vendor/apps/MiuiCamera/MiuiCamera-vendor.mk)

# Camera
PRODUCT_PACKAGES += \
    MiuiCamera

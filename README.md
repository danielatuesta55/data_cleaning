# data_cleaning-- Table: public.NashvilleHousing 
```
-- DROP TABLE public."NashvilleHousing ";

CREATE TABLE public."NashvilleHousing "
(
    "UniqueID" bigint,
    "ParcelID" character varying COLLATE pg_catalog."default",
    "LandUse" character varying COLLATE pg_catalog."default",
    "PropertyAddress" character varying COLLATE pg_catalog."default",
    "SaleDate" date,
    "SalePrice" bigint,
    "LegalReference" character varying COLLATE pg_catalog."default",
    "SoldAsVacant" character varying COLLATE pg_catalog."default",
    "OwnerName" character varying COLLATE pg_catalog."default",
    "OwnerAddress" character varying COLLATE pg_catalog."default",
    "Acreage" numeric,
    "TaxDistrict" character varying COLLATE pg_catalog."default",
    "LandValue" bigint,
    "BuildingValue" bigint,
    "TotalValue" bigint,
    "YearBuilt" integer,
    "Bedrooms" integer,
    "FullBath" integer,
    "HalfBath" integer
)

TABLESPACE pg_default;

ALTER TABLE public."NashvilleHousing "
    OWNER to postgres;


SELECT * FROM public."NashvilleHousing "
```
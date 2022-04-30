# Summary
- Description 
- Fields
- Methods

## Description
Demons info in stock (visible through menus)

datUnitWork_t inherits from datUnitWork_s which has all the fields.
# Fields
## uint flag
## ushort id
Demon ID
## ushort hp
Demon HP
## ushort maxhp
Demon max HP
## ushort mp
Demon MP
## ushort maxmp
Demon max MP
## ushort badstatus

## uint exp
Demon experience
## ushort level
Demon level
## sbyte[] param
Demon stats  
[Strength, ???, Magic, Vitality, Agility, Luck]
## sbyte[] skillparam

## ushort uniqueid

## ushort reserve1

## ushort reserve2

## char[] namecode

## int skillcnt
Demon number of skills (learnt only)
## int[] skill
Demon skill list (learnt only)
## short nowcommand

## ushort nowindex

## short nowtarea

## short nowtform

## short prevcommand

## ushort previndex

## short prevtarea

## short prevtform

## sbyte[] mitamaparam

## sbyte[] levelupparam

## ushort[] keisyoskill
Demon inherited skills from fusion
## byte[] keiattr

## ushort hensinmae

## ushort[] getdevilhearts
Magatama ?
## uint hensinmaeexp

## char[] fullnamecode
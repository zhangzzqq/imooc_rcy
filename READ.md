
## recyclerview基本用法
SimpleHorListAdapter
simpleAdater

## 多类型 viewholder
 case DataModel.TYPE_ONE:
return  new TypeOneViewHolder(layoutInflater.inflate(R.layout.item_one,parent,false));
case DataModel.TYPE_TWO:
return  new TypeTwoViewHolder(layoutInflater.inflate(R.layout.item_two,parent,false));
case DataModel.TYPE_THREE:
return  new TypeThreeViewHolder(layoutInflater.inflate(R.layout.item_three,parent,false));





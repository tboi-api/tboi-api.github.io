# tboi-api.github.io

/lang/categry/name.json
ex:
	/en/item/brimstone.json

pools:
	??: can be replaced by nh (normal / hard) or gd (greed / greedier)
	"?? treasure"
	"?? shop"
	"?? secret"
	"?? ultra secret"
	"?? devil"
	"?? angel"
	"?? babyshop"
	"?? planetarium"
	"?? library"
	"?? cursed"
	"?? boss"
	"?? golden chest"
	"?? red chest"
	"?? beggar"
	"?? devil beggar"
	"?? key master"
	"?? bomb bum"
	"?? crane game"
	"?? shell game"
	"?? rotten beggar"
	"?? battery num"
	"?? old chest"
	"?? wooden chest"
	"?? mom's chest"
	
transformation:
	"Guppy"
	"Beelzebub"
	"Super Bum"
	"Yes Mother?"
	"Bob"
	"Fun Guy"
	"Leviathan"
	"Conjoined"
	"Spun"
	"Seraphim"
	"Oh Crap"
	"Bookworm"
	"Spider Baby"
	"Adult"
	"Stompy"


item format:
{
	name:
	id:
	quality: (as str [0-4])
	description: (in game description ex: brimstone: "blood laser barrage")
	pool: (list of str)
	image: (str)
	transformartion:
}
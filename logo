#function

function colors {
  GREEN="\e[32m"
  NORM="\e[0m"
}

center()
{ 
IFS=""
while read L
do
printf "%b\n" $(printf "%.$((($(tput cols)-${#L})/2))d" 0 | sed 's/0/ /g')$L
done
}

colors

function logo {
echo -e "${GREEN}─────╔═══╗╔══╗╔╗─╔╗╔══╗─╔══╗╔══╗╔╗─╔╗─────${NORM}" | center
echo -e "${GREEN}─────║╔═╗║║╔╗║║╚═╝║║╔╗╚╗╚╗╔╝║╔╗║║╚═╝║─────${NORM}" | center
echo -e "${GREEN}─────║╚═╝║║╚╝║║╔╗─║║║╚╗║─║║─║║║║║╔╗─║─────${NORM}" | center
echo -e "${GREEN}─────║╔══╝║╔╗║║║╚╗║║║─║║─║║─║║║║║║╚╗║─────${NORM}" | center
echo -e "${GREEN}─────║║───║║║║║║─║║║╚═╝║╔╝╚╗║╚╝║║║─║║─────${NORM}" | center
echo -e "${GREEN}─────╚╝───╚╝╚╝╚╝─╚╝╚═══╝╚══╝╚══╝╚╝─╚╝─────${NORM}" | center

}

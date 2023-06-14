Major{
    banner:img;
    Name: string;
    Address: string;
    price: integer;
    min size:int;
    max size:int;
    configurations: string;
    status: string;
    Rera No.: string;
    Description: paragraph(string);
    brochure:url;
    video:media(link);
    highlight{
        1:string;
        2:string;
        3:string;
        4:string;
        5:string;
        6:string;
        7:string;
        8:string;
        9:string;
        image: img;
    }
    amenities{
        1{
            a-image:img;
            text: string:
        }
        2{
             a-image:img;
            text: string:

        }
        3{
             a-image:img;
            text: string:

        }
        4{
             a-image:img;
            text: string:

        }
       5 {
             a-image:img;
            text: string:

        }
    }
    Cards{
        1{
            card-image:img;
            tagline:string;
            location:string;
            type:string;
            BHK:int;
            area: int

        }
        2{
            card-image:img;
            tagline:string;
            location:string;
            type:string;
            BHK:int;
            area: int

        }
        3{
            card-image:img;
            tagline:string;
            location:string;
            type:string;
            BHK:int;
            area: int

        }
    }




}
